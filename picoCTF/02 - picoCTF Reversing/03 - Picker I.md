## Descripción

- This service can provide you with a random number, but can it do anything else?
## Solución

- descargue el archivo de python del reto para analizar como funcionaba el codigo
- revisando el script me di cuenta que usaba una funcion vulnerable que ejecutaba directo lo que el usuario escribia
- explorando el mismo codigo encontre una funcion llamada win que servia para leer el archivo de la bandera
- abri la terminal y me conecte al servidor usando el comando de netcat
- en cuanto el programa me pidio ingresar un dato escribi win para forzar la ejecucion de esa funcion
- el servidor me respondio pero me escupio la bandera oculta en puros codigos hexadecimales
- copie toda esa cadena de numeros y la pase por un traductor de hex a texto en internet
## Notas adicionales 

## Referencias 