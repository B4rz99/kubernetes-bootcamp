Objetivo: Practicar la ejecución de contenedores interactivos.

Descarga la imagen oficial de node:18-alpine.
Ejecuta un contenedor en modo interactivo (-it) y ejecuta node directamente.
Dentro del intérprete de Node, escribe console.log("Hola desde Docker!") y verifica que funciona.
Luego, crea un archivo local app.js que imprima "¡Aprendiendo Docker!" y montalo en un contenedor Node para ejecutarlo, este paso puede ser con un docker volume o creando una docerfile para copiar o mover el app.js

