FROM openjdk:8-jdk-alpine
COPY discoverify-config-server-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom -env","-jar","/app.jar"]