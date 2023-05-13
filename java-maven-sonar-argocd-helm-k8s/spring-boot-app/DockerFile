FROM: adoptopenjdk:11-jdk-hotspot:alpine
ARG: artifact=target/spring-boot-web.jar
WORKDIR: /opt/app
COPY: ${artifact} app.jar
ENTRYPOINT: ["java", "-jar", "app.r"]
