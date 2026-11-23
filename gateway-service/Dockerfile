FROM eclipse-temurin:21-jre
WORKDIR /app
COPY target/gateway-service.jar app.jar
EXPOSE 8765
ENTRYPOINT ["java", "-jar", "app.jar"]
