FROM eclipse-temurin:17-alpine

# Argumento para el archivo JAR
ARG JAR_FILE

# Copia el JAR específico al contenedor
COPY ${JAR_FILE} app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","/app.jar"]