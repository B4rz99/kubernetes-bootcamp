Objetivo: Practicar la orquestación de múltiples servicios con Docker Compose.
Descripción:
Crea un archivo docker-compose.yml que defina dos servicios:

Web: Usa php:apache y mapea un directorio local con un index.php (puede ser un "Hola Mundo") al directorio /var/www/html del contenedor.
DB: Usa mysql:8.0 y configura variables de entorno para:
Contraseña root: 1234
Base de datos predeterminada: testdb
Levanta los servicios con docker compose up y verifica que la app web funciona accediendo a http://localhost:8080.

