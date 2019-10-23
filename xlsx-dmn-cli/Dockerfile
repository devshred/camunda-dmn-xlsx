FROM openjdk:8-jre-alpine

ARG JAR_FILE
ADD target/${JAR_FILE} /app.jar

VOLUME /data

ENTRYPOINT ["java","-jar","/app.jar"]