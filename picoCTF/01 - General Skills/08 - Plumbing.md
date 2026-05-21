## Descripción

- A veces es necesario gestionar datos de procesos fuera de un archivo. nos pide encontrar la bandera en un servidor que nos bombardea con líneas de texto basura que nos dicen que ESA linea definitivamente no es la bandera 
## Solución

- usamos el comando nc para conectarnos al servidor y al puerto y agregamos el comando | grep pico en la misma linea para buscar la bandera entre todas las lineas "basura"
## Notas adicionales 

## Referencias 