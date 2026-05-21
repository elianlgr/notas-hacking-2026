## Descripción

- Can you figure out how this program works to get the flag?
## Solución

- descargue el codigo fuente en c y el binario para buscar vulnerabilidades
- al revisar el codigo vi que el programa te pide ingresar una direccion de memoria para ejecutar lo que haya ahi
- use el comando readelf -s sobre el binario descargado y lo filtre con grep para buscar la funcion win
- la terminal me arrojo que la funcion estaba en la direccion de memoria 40129e
- abri la terminal y me conecte al servidor del reto con el comando de netcat
- el programa me pidio ingresar la direccion y escribi 40129e
- el sistema hizo el salto a esa direccion y ejecuto la funcion imprimiendo la bandera
## Referencias 