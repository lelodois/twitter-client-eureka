# twitter-eureka

### Build docker

- mvn install
- docker build -t twcli-eureka-docker .
- docker run --net twclientnet --ip 172.18.0.21 -d -p 8091:8091 {tag}

