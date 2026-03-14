# Use Eclipse Temurin Java 17 JDK
FROM eclipse-temurin:17-jdk

# Set working directory inside the container
WORKDIR /app

# Copy the compiled Spring Boot jar into the container
COPY target/*.jar app.jar

# Expose the port your Spring Boot app runs on
EXPOSE 9090

# Run the Spring Boot application
ENTRYPOINT ["java", "-jar", "/app/app.jar"]