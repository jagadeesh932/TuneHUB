# Use a lightweight Java 17 image
FROM openjdk:17-jdk-slim

# Set working directory inside container
WORKDIR /app

# Copy the built JAR file from the host machine (created in pipeline)
COPY target/musichub-app.jar app.jar

# Expose the application port
EXPOSE 8080

# Command to run the Spring Boot app
ENTRYPOINT ["java", "-jar", "app.jar"]
