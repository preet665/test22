# Use a lightweight Alpine Linux with OpenJDK 8
FROM openjdk:8-jdk-alpine

# Set the working directory to /app
WORKDIR /app

# Copy the executable JAR file and other files to the container
COPY target/devops-exam-0.0.1-SNAPSHOT.jar ./
COPY src/main/resources/application.properties ./src/main/resources/

# Expose the port that the application will listen on
EXPOSE 8083

# Run the JAR file
CMD ["java", "-jar", "devops-exam-0.0.1-SNAPSHOT.jar"]
