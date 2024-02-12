## Instalación

1. Ve al [video tutorial de Amigos Code](https://youtu.be/vtPkZShrvXQ?si=mxMoycPxNE7Ko6Jn) en YouTube.

2. Sigue las instrucciones del video para clonar el repositorio y configurar el proyecto en tu máquina local.

3. Asegúrate de tener Docker instalado en tu máquina.

4. Inicia una instancia de PostgreSQL utilizando Docker:
5. docker run --name postgres-db -e
6. POSTGRES_PASSWORD=your_password -d -p 5432:5432 postgres
7. Abre el proyecto en tu IDE preferido (por ejemplo, IntelliJ IDEA, Eclipse).
8. Configura las propiedades de la base de datos en el archivo `application.properties`:
9. spring.datasource.url=jdbc:postgresql://localhost:5432/db_name
10. spring.datasource.username=your_username
11. spring.datasource.password=your_password
12. Ejecuta la aplicación Spring Boot.
