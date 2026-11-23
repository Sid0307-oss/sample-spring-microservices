FROM eclipse-temurin:21-jre
WORKDIR /app
COPY target/customer-service.jar app.jar
EXPOSE 3333
ENTRYPOINT ["java", "-jar", "app.jar"]
