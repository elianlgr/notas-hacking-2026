## Descripción

- I found a web app that can help process images: PNG images only!
## Solución

- Creé un archivo llamado shell.png.php que contenía la palabra PNG al inicio seguida de un pequeño script en PHP, para engañar al servidor y que lo aceptara como si fuera una imagen real.
    
- Luego, utilicé el comando curl para enviar y subir este archivo directamente al formulario de la aplicación web.
    
- Una vez que el servidor me confirmó que el archivo se había subido con éxito, intenté ejecutar un comando find para buscar cualquier archivo que tuviera la palabra flag en su nombre, pero me di cuenta de que solo aparecían archivos internos del sistema.
    
- Al deducir que el archivo que buscaba tenía un nombre diferente, cambié mi estrategia y ejecuté otro comando para buscar todos los archivos terminados en .txt dentro de la carpeta principal del servidor web (/var/www/html/).
    
- Gracias a esa búsqueda, descubrí un archivo con un nombre aleatorio y sospechoso llamado MFRDAZLDMUYDG.txt.
    
- Finalmente, usé el comando cat a través de la URL de mi webshell para leer el contenido de ese archivo específico, lo que me permitió obtener la bandera y resolver el reto.
## Notas adicionales 

## Referencias 