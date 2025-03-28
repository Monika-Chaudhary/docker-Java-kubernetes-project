FROM openjdk:9-jre
WORKDIR /app
COPY target/shopfront-SNAPSHOT-1.0.jar app.jar
EXPOSE 8010
#CMD ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "app.jar"]
CMD ["java", "-jar", "app.jar"]
