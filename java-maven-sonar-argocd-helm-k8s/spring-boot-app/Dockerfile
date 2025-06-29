# Use Maven + Java 17 base image
FROM maven:3.8.6-eclipse-temurin-17

# Set working directory inside the container
WORKDIR /opt/app

# Copy the built JAR file to the container
COPY target/spring-boot-web.jar app.jar

# Run the Spring Boot application
ENTRYPOINT ["java", "-jar", "app.jar"]
