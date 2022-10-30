FROM java:8

WORKDIR app

COPY hello-springboot/target/docker/*.jar app.jar

CMD ["java", "-jar", "app.jar"]
