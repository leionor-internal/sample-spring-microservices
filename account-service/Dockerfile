# Use the modern Java 21 runtime image
FROM eclipse-temurin:21-jdk-jammy

MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>

# Copy your compiled jar into the container image
ADD target/account-service.jar account-service.jar

# Run the application
ENTRYPOINT ["java", "-jar", "/account-service.jar"]

EXPOSE 2222
