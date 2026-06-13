## Descripción

- Can you get the flag?
## Solución

- Abrí la terminal y realicé una petición a la página principal para analizar su código fuente usando: curl [http://saturn.picoctf.net:52659/](http://saturn.picoctf.net:52659/)
    
- Al leer el código HTML devuelto en la consola, noté que la página incluía dos archivos externos llamados style.css y script.js, lo cual le daba sentido al nombre del reto.
    
- Ejecuté un comando para descargar y leer el archivo de estilos usando: curl [http://saturn.picoctf.net:52659/style.css](https://www.google.com/search?q=http://saturn.picoctf.net:52659/style.css)
    
- En esa respuesta encontré la primera mitad de la bandera oculta dentro de un comentario de formato CSS.
    
- Luego, ejecuté otro comando para descargar y leer el archivo de código usando: curl [http://saturn.picoctf.net:52659/script.js](https://www.google.com/search?q=http://saturn.picoctf.net:52659/script.js)
## Notas adicionales 

## Referencias 
