Objetivo: Practicar el manejo de datos persistentes.

Crea un volumen llamado datos-mysql:

bash
docker volume create datos-mysql

Ejecuta un contenedor MySQL (mysql:8.0) que:

Use el volumen datos-mysql para /var/lib/mysql.
Configure credenciales con variables de entorno (MYSQL_ROOT_PASSWORD, MYSQL_DATABASE).
Detén el contenedor y crea uno nuevo reutilizando el mismo volumen. Verifica que la base de datos persiste.

