# Usar una imagen de Java 17
FROM eclipse-temurin:17-jdk

# Establecer el directorio de trabajo
WORKDIR /app

# Copiar el JAR generado al contenedor
COPY target/*.jar app.jar

# Comando para ejecutar la aplicación
ENTRYPOINT ["java", "-jar", "app.jar"]
