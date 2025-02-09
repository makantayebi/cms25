# Use OpenJDK as base image
FROM openjdk:21-jdk-slim

# Set working directory
WORKDIR /app

# Copy built JAR from target folder (Ensure it's built first)
COPY target/*.jar app.jar

# Expose the backend port
EXPOSE 8080

# Run the application
CMD ["java", "-jar", "app.jar"]