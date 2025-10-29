FROM openjdk:17-jdk-slim
WORKDIR /app
COPY . .
COPY target/musichub-app.jar musichub-app.jar
EXPOSE 8080
ENTRYPOINT ["java" , "-jar" , "musichub-app.jar"]
