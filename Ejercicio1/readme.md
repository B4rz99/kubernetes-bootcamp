Objetivo: Practicar la creación de imágenes personalizadas usando un Dockerfile.

Descripción: Crea un Dockerfile para una imagen basada en nginx:alpine.

Personaliza la imagen para que:
Copie un archivo index.html (que debes crear) en /usr/share/nginx/html.
Exponga el puerto 80.
Use la instrucción CMD para iniciar nginx en primer plano.
Construye la imagen con el nombre mi-nginx.
Ejecuta un contenedor basado en esa imagen y verifica que puedas acceder al sitio web en http://localhost:8080 (mapeando el puerto 80 del contenedor al 8080 del host).

