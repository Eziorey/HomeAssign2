FROM openjdk:8-jdk-alpine AS Ruiyang
RUN addgroup -S spring && adduser -S spring -G spring
User spring:spring \
ARG AimFile=node-hello-master/*.js
COPY ${AR_FILE} app.jar
ENTRYPOINT ["java","-jar","app.jar"]