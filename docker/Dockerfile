FROM eclipse-temurin:17-jdk-alpine

ENV SPRING_PROFILES_ACTIVE=development

COPY java-jungle-0.0.1.jar /app.jar

ENTRYPOINT ["java","-jar","/app.jar"]