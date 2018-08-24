# twitter-eureka

### Build docker
- java -jar target/twitter-client-eureka-0.0.1-SNAPSHOT.jar –server.port=8051
- docker build -t twcli-eureka .
- docker run -d -p 8051:8051 {tag}
