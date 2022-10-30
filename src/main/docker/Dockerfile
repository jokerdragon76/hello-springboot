FROM java:8

WORKDIR app

COPY target/docker/*.jar app.jar

CMD ["java", "-jar", "app.jar"]
