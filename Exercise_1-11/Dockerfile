FROM openjdk:8

WORKDIR /usr/src/app

# Copy all of the source code
COPY . .

RUN ./mvnw package
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]

EXPOSE 8080
