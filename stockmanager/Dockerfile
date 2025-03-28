FROM openjdk:8-jre
WORKDIR /app
COPY target/stockmanager-SNAPSHOT-1.0.jar app.jar
EXPOSE 8030
#CMD ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "app.jar"]
CMD ["java", "-jar", "app.jar"]
