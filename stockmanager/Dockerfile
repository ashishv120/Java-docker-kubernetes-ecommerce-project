#As this is Microservice - writing Dockerfile for each of it.
#This Dockerfile is for stockmanager service
FROM openjdk:8-jre
ADD target/stockmanager-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8030
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar","server"]
