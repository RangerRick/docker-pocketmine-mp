docker build -t dliefbroer/docker-pmmp:v1 .

docker run --name=pmmp -d -v /<directory>:/pocketmine/PocketMine-MP -p 19132:19132/udp -p 19132:19132/tcp dliefbroer/docker-pmmp:v1

Download any newer version of the pmmp .phar file to the mapped directory and restart the container.