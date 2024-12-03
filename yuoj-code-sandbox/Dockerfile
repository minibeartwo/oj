FROM openjdk:8-jdk-alpine

# Copy local code to the container image.
WORKDIR /app

COPY yuoj-code-sandbox-0.0.1-SNAPSHOT.jar /app/yuoj-code-sandbox-0.0.1-SNAPSHOT.jar

EXPOSE 8090

# Run the web service on container startup.
CMD ["java", "-jar", "/app/yuoj-code-sandbox-0.0.1-SNAPSHOT.jar"]
