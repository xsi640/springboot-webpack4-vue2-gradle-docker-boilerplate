FROM openjdk:8-jdk-alpine
ADD ["fixed-app.jar", "/app/app.jar"]
WORKDIR /app
ENTRYPOINT java -Djava.security.egd=file:/dev/./urandom -jar app.jar
EXPOSE 8080