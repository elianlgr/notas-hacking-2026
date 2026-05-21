## Descripción

- Download this disk image and find the flag.
- Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.
## Solución

- descargamos el archivo con el comando wget 
- hacemos un ls para ver el archivo descargado y usaos el comando gzip para descomprimir la imagen 
- usamos el comando mmls para obtener mas información
- usamos el comando fls "nombre del archivo" -o "datos obtenidos"
- ahora usamos el comando grep combinado con el comando fls para hacer una búsqueda de el archivo con la bandera fls "nombre del archivo" -o "datos obtenidos" -r | grep "flag"
- al ejecutar el comando anterior aparecen nombres de archivos con números hacemos la prueba con alguno de ellos para obtener la bandera con el comando icat "nombre del archivo" -o 360448 2371 y obtendremos la bandera 
## Notas adicionales 

## Referencias 