FROM eclipse-temurin:17
COPY /target/*.jar app.jar
ENV SPRING_PROFILES_ACTIVE docker
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "/app.jar"]