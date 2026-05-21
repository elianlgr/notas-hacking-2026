## Descripción

- Use `srch_strings` from the sleuthkit and some terminal-fu to find a flag in this disk image.
- nos da un archivo para desargar y resolver el reto 
## Solución

- descargamos el archivo con wget 
- hacemos un ls para ver el archivo descargado y aplicamos el comando unzip para descomprimirlo 
- usamos el comando srch_strings "nombre del archivo" | grep "pico" para buscar las cadenas que empiecen con la palabra clave pico 
## Notas adicionales 

## Referencias 