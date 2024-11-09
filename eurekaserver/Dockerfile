FROM openjdk:17-jdk-slim

ARG JAR_FILE=target/eurekaserver-0.0.1.jar
COPY ${JAR_FILE} eurekaserver.jar
EXPOSE 8065
ENTRYPOINT ["java", "-jar", "eurekaserver.jar"]