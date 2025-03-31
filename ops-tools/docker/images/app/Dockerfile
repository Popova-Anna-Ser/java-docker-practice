FROM openjdk:17-jdk-slim

WORKDIR /app

COPY ./target/docker-practice-java-0.0.1-SNAPSHOT.jar /app/app.jar

EXPOSE 8888

CMD ["java", "-Dspring.profiles.active=docker", "-jar", "/app/app.jar"]

