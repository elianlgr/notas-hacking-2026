## Descripción

- We found this packet capture. Recover the flag.
- nos da un archivo para descargar y resolver el reto 
## Solución

- abrimos le archivo en la herramienta wireshark 
- filtramos todos los paquetes que su puerto destino sea el 22
- los últimos 3 dígitos de el puerto de origen son los caracteres de la bandera en ascii
- usamos un bloque de código en python para que lo haga automáticamente 
## Notas adicionales 

## Referencias 