FROM openjdk:8-jre
WORKDIR /app
COPY target/productcatalogue-SNAPSHOT-1.0.jar app.jar
COPY product-catalogue.yml .
EXPOSE 8020
#CMD ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "app.jar", "server", "product-catalogue.yml"] 
CMD ["java", "-jar", "app.jar", "server", "product-catalogue.yml"]
