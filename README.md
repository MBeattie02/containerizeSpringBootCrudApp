# containerizeSpringBootCrudApp

Create a simple Spring Boot App and Dockerize it 

mvn clean install to build jar

docker build -t <NAME_OF_IMAGE>:<VERSION> . 
docker build -t containerize-spring-boot-app .

docker tag containerize-spring-boot-app mabeatti/containerize-spring-boot-app

docker push mabeatti/containerize-spring-boot-app:latest
docker push mabeatti/containerize-spring-boot-app

docker run -p 8090:8080 mabeatti/containerize-spring-boot-app:latest

🐳 https://hub.docker.com/repository/docker/mabeatti/containerize-spring-boot-app/general
