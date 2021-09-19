# Learning
I fetched the info from https://spring.io/guides/gs/spring-boot-docker/
then after Application.java creation ran the following commands in app directory context

 # Package
`mvn package`

# To test the app locally 
`java -jar target/spring-boot-docker-initial-0.0.1-SNAPSHOT.jar`

# Docker build 
`docker build . -t smanaqvi83/docker-learning` 

# Docker run 

`docker run -p 8080:8080  smanaqvi83/docker-learning`

