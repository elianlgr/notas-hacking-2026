## Descripción

- Find the flag being held on this server to get ahead of the competition
## Solución

- Analicé el nombre del reto "GET aHEAD", deduciendo que era una pista directa para utilizar el método de petición HTTP `HEAD`.
    
- Ejecuté el comando `curl -I http://wily-courier.picoctf.net:55081/` en mi terminal para enviar la solicitud `HEAD` al servidor y obtener solo las cabeceras.
    
- Revisé la salida arrojada por el comando, la cual contenía los metadatos y las cabeceras de respuesta HTTP.
## Notas adicionales 

## Referencias 
