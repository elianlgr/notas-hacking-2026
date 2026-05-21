## Descripción

- Can you figure out how this program works to get the flag?
## Solución

- descargue el archivo de python para analizar el codigo fuente y ver los cambios
- note que habian cambiado la logica poniendo un menu estricto de 4 opciones
- me di cuenta que la opcion 3 permitia sobreescribir el valor de cualquier variable sin seguridad
- abri la terminal y me conecte al servidor del reto usando el comando de netcat
- escogi la opcion 3 y sobreescribi la variable getrandomnumber asignandole el valor de la funcion win
- luego ejecute la opcion 4 que ahora en lugar de dar un numero ejecuto la lectura de la bandera
- el servidor me entrego la bandera oculta en formato hexadecimal
- copie esos codigos y use un traductor en linea para pasarlos a texto normal
## Notas adicionales 

## Referencias 