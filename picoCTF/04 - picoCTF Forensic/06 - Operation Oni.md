## Descripción

- Download this disk image, find the key and log into the remote machine.

- Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.
## Solución

- descargamos la imagen con un wget 
- desempaquetamos un con gzip -d
- mmls 
- usamos el comando fls -o y el inicio de la imagen 
- listamos el contenido de la carpeta root
- nos dirigimos al directorio ssh y vemos llaves publicas y privadas 
- usamos el comando icat -o y lo mandamos a un archivo en disco 
- le damos permisos de solo lectura 
- y entramos al servidor con el archivo donde tenemos la llave ssh -i key_file -p 49229 ctf-player@saturn.picoctf.net
## Notas adicionales 

## Referencias 