Objetivo: Identificar y corregir errores en un Dockerfile.
Descripción:
Se te proporciona el siguiente Dockerfile con errores:

Dockerfile
FROM ubuntu
RUN apt update && apt install -y curl
COPY script.sh /scripts/
CMD ["/scripts/script.sh"]

Tareas:

Identifica los errores (ej: falta -y en apt install, directorio /scripts no existe, script.sh no tiene permisos).
Corrige el Dockerfile y construye una imagen funcional.
Crea un script.sh simple (ej: echo "Script funciona!") y verifica que el contenedor lo ejecuta correctamente.

