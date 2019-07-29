FROM openjdk:8-jdk-slim
COPY ./build/libs/spring-boot-vue-0.0.1-SNAPSHOT.jar /opt/server.jar
WORKDIR /opt
CMD ["java", "-jar", "/opt/server.jar"]
