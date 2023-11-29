FROM openjdk:19-alpine
COPY target/*.jar app.jar
EXPOSE 8034
ENTRYPOINT ["java", "-jar", "app.jar"]