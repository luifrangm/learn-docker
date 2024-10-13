FROM openjdk:17-jdk-slim
ARG JAR_FILE=tagert/learn-docker-1.0.jar
COPY ${JAR_FILE} app_learn_docker.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_learn_docker.jar"]
