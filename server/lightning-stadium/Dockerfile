FROM openjdk:11-jdk-slim

MAINTAINER EvansShamChan

COPY /target/lightning-stadium-0.0.1.jar /lightning-stadium.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "lightning-stadium.jar"]