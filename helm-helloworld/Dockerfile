# Gebruik een OpenJDK-base image
FROM openjdk:20-jdk-slim

# Voeg de Java applicatie toe aan de container
COPY HelloWorld.java /app/HelloWorld.java

# Compileer de Java applicatie
WORKDIR /app
RUN javac HelloWorld.java

# Voer de Java applicatie uit
CMD ["java", "HelloWorld"]