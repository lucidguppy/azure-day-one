FROM openjdk:21
MAINTAINER "mattkaras.info"

COPY target/data-loader-1.0-SNAPSHOT-shaded.jar app.jar
ENTRYPOINT ["java", "-jar","/app.jar"]