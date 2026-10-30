# Utiliser Java 17, requis par ton projet
FROM eclipse-temurin:17-jre

WORKDIR /app

# Configurer le port de Spring Boot
ENV SERVER_PORT=8081

# Copier le fichier JAR compilé
COPY target/demo-0.0.1.jar /app.jar

# Exposer le port
EXPOSE 8081

# Démarrer l'application
ENTRYPOINT ["java", "-jar", "/app.jar"]
