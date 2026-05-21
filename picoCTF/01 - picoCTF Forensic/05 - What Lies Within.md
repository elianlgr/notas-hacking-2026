## Descripción

- There's something in the building. Can you retrieve the flag?
- nos dará un archivo para descargar y poder resolver el reto 
## Solución

- descargamos al archivo y al aplicarle file al archivo vamos que es un archivo png 
- al abrirla notamos que es una técnica de esteganografía 
- una de las formas para encontrar el mensaje oculto es simplemente entrar a una pagina de internet donde se pueda subir la imagen con el mensaje oculto y lo descifrara solo 
- tambien se puede usar una herramienta en la terminal llamada zsteg que de igual manera que la pagina web, busca el mensaje indicado
- usamos el comando zsteg -a "nombre de la imagen" | grep pico y así obtendremos la bandera 
## Notas adicionales 

- la esteganografía implica esconder información sensitiva dentro de un archivo o mensaje ordinario (no secreto) para que no sea detectado, luego la información confidencial se extrae del archivo en su destino evitando así la detección  
## Referencias 