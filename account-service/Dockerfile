FROM eclipse-temurin:21-jre
WORKDIR /app
COPY target/account-service.jar app.jar
EXPOSE 2222
ENTRYPOINT ["java", "-jar", "app.jar"]
