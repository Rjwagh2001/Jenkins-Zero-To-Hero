
# Java 21 runtime
FROM eclipse-temurin:21-jre

WORKDIR /opt/app

# Copy the Spring Boot executable JAR
ARG artifact=target/spring-boot-web.jar
COPY ${artifact} app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
