FROM openjdk:18-alpine

WORKDIR /app

COPY ./target/*.jar app.jar

EXPOSE 8082

CMD ["java", "-jar", "app.jar"]

