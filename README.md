# Run using docker
1. docker build . --tag zuul-api-gateway
2. docker run -it -p8080:8080 zuul-api-gateway:latest

# Run native
1. gite clone https://gitlab.com/GLG204/administration/backend/zuul-api-gateway.git
2. cd zuul-api-gateway
3. mvn package
4. java -Dspring.profiles.active=development -jar target/demo.jar

###### Note: copy src/main/resources/application-development.yml to target directory
