FROM openjdk:17
WORKDIR /app
COPY ./target ./

EXPOSE 8080
ENTRYPOINT ["java", "-jar", "words.jar"]