## Descripción

- Download this disk image and find the flag.
- Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.
## Solución

- descargamos el enlace en la carpeta donde vamos a trabajar con el comando wget 
- hacemos un ls y vemos un archivo zip usamos el comando unzip -d para descomprimirlo y nos da la imagen que hay dentro 
- con el comando mmls nos dira las particiones que existen
- usamos el comando fls disk.flag.img -o 411648 -r | grep flag para buscar la carpeta que tenga la bandera 
- buscando dentro de los archivo encontramos la bandera cifrada 
- con el comando vi files haremos una busqueda con las palabras clave
- usamos icat disk.flag.img -o 411648 1875 para ver el historial
- usamos este comando para desencriptar openssl aes256 -salt -out flag.txt -in flag.txt.enc -k unbreakablepassword1234567
- usamos este comando para que mande la bandera a esa dirección icat disk.flag.img -o 411648 1782 > flag.txtnc
- aplicamos un cat a la dirección y obtenemos la bandera 
## Notas adicionales 

## Referencias 