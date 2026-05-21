## Descripción

- Can you figure out how this program works to get the flag?
## Solución

- descargue el codigo fuente de python y vi que le habian puesto un filtro para bloquear la palabra win
- me di cuenta que el programa seguia usando la funcion vulnerable eval que ejecuta comandos de python directamente
- abri la terminal y me conecte al servidor del reto con el comando de netcat
- tuve un pequeño error al intentar meter la funcion eval vacia pero entendi como funcionaba el input
- me volvi a conectar y decidi pedirle a python que abriera y leyera el texto de la bandera por mi
- cuando el programa me pidio el dato escribi el comando print(open('flag.txt').read())
- el servidor ejecuto mi instruccion saltandose el filtro y me escupio la bandera en la consola
## Notas adicionales 

## Referencias 