## Descripción

- We found this packet capture and key. Recover the flag.
- es un reto similar al anterior
## Solución

- añadimos el archivo de la llave al puerto 443 
- el trafico encriptado se transforma en paquetes http que ahora se pueden leer
- filtramos con http para ver solo el trafico web 
- buscamos archivos de imagen o script 
- extraemos todos los archivos que filtramos del servidor 
- ahora que tenemos los archivos buscamos la bandera con el comando grep y la palabra clave pico 
## Notas adicionales 

## Referencias 