## Descripción

- This is a really weird text file. Can you find the flag?
- nos da un archivo de texto para descargar e iniciar la búsqueda de la bandera 
## Solución

- al descargar el archivo a simple vista pareciera un archivo .txt pero al aplicarle un file nos dice linux que es un archivo png
- usamos el comando xxd concatenado con head para ver si hay alguna firma existente en la cabecera del archivo 
- después de eso cambiamos la extensión del archivo con el comando mv 
- al abrir el archivo corregido encontramos la bandera 
## Notas adicionales 

## Referencias 
