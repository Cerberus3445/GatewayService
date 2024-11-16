FROM openjdk:21
LABEL authors="egor"

VOLUME /tmp
WORKDIR /app
ADD maven/gateway-service-0.0.1-SNAPSHOT.jar /app/gateway.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "gateway.jar"]