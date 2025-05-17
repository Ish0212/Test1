FROM eclipse-temurin:17-jdk

WORKDIR /app

COPY . /app

RUN ./mvnw package

CMD ["java", "-jar", "target/weather-discord-bot-1.0-SNAPSHOT-shaded.jar"]
