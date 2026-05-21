## Descripción

- Decode this message from the moon.
- nos da un archivo para descarga y encontrar la bandera 
- pareciera que quiere que encontremos imagenes que vienen de la luna pero el archivo que nos da es un archivo de audio 
## Solución

- descargamos el archivo y al aplicarle un file nos encontramos con un archivo de audio 
- usamos el comando strings sobre el para ver si hay algo escondido pero no hay pistas o respuestas positivas 
- usaremos un decodificador de audio de formato sstv que encontramos en un repositorio de github
- clonamos el repositorio e instalamos el script de instalación
- analizando la sintaxis para usar la herramienta instalada usamos el comando sstv -d "nombre del archivo" -o result.png
- abrimos la imagen y ahí viene escrita la bandera 
## Notas adicionales 

## Referencias 