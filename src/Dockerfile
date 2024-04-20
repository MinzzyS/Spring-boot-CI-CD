FROM openjdk:17-alpine
EXPOSE 8080
ADD target/spring-boot-hello-world-example-0.0.1-SNAPSHOT.jar spring-boot-docker.jar
ENTRYPOINT ["java", "-jar", "/spring-boot-docker.jar"]