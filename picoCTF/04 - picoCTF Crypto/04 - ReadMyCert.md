## Descripción

- How about we take you on an adventure on exploring certificate signing requests Take a look at this CSR file
## Solución

- descargar el archivo csr desde el enlace proporcionado en el reto
-  abrir la terminal en la ubicacion donde se descargo el archivo
- utilizar la herramienta openssl con el comando openssl req -in nombre_del_archivo.csr -noout -text para inspeccionar su contenido
- leer la salida generada en la terminal y buscar la seccion subject del certificado
- copiar la bandera que se encuentra visible como texto plano dentro de esa seccion
- enviar la bandera encontrada a la plataforma de picoctf
## Notas adicionales 

## Referencias 