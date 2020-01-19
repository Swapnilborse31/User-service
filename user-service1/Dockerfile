
FROM openjdk:8u212-jdk-slim

LABEl maintainer="swapnilborse31@gmail.com"

VOLUME /tmp

EXPOSE 8083

ARG JAR_FILE=target/user-service1-0.0.1-SNAPSHOT.jar

ADD ${JAR_FILE} user-service1-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/user-service1-0.0.1-SNAPSHOT.jar"]
