# Usar una imagen base de Java
FROM openjdk:11-jre-slim

# Establecer el directorio de trabajo en el contenedor
WORKDIR /app

# Copiar el archivo JAR al contenedor
COPY microservicio-evaluacion-backend-1.0-SNAPSHOT.jar /app/HolaMundo.jar

# Exponer el puerto 8080
EXPOSE 8080

# Comando para ejecutar la aplicación
ENTRYPOINT ["java", "-jar", "HolaMundo.jar"]