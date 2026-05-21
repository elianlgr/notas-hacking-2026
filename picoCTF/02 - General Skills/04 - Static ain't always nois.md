## Descripción

- nos pide encontrar la bandera del cft dentro de un archivo binario 
## Solución

- usamos el comando `file` para identificar el tipo de archivo del binario y el script
- le dimos permisos al script con chmod +x  y lo ejecutamos para extraer el texto legible del binario
- finalmente, usamos de forma directa el comando strings sobre el archivo junto con grep pico para filtrar e imprimir la bandera rápidamente
## Notas adicionales 

## Referencias 