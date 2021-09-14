FROM openjdk:8-jdk-alpine
MAINTAINER Ruiyang <s3679150@student.rmit.edu.au>
RUN addgroup -S spring && adduser -S spring -G spring
User spring:spring \
ARG AimFile=target/*.jar
COPY ${AR_FILE} app.jar
ENTRYPOINT ["java","-jar","app.jar"]