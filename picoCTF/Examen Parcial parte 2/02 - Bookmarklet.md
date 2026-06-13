## Descripción

- Why search for the flag when I can make a bookmarklet to print it for me?
## Solución

- Para evitar que la terminal corrompiera los datos al mostrarlos en pantalla, decidí automatizar la extracción del código.
    
- Descargué la página web directamente a un archivo local usando el comando curl y lo guardé como page.html.
    
- Utilicé la herramienta awk para buscar y recortar únicamente el bloque de la función de JavaScript, guardándolo en un nuevo archivo llamado script.js.
    
- Limpié el texto del archivo ejecutando el comando sed para borrar la palabra javascript que sobraba.
    
- Volví a utilizar el comando sed para cambiar la palabra alert por console punto log, adaptando así el código para que funcionara fuera del navegador.
    
- Ejecuté el script limpio con el comando node script.js, lo que procesó la cadena original intacta y me devolvió la bandera
## Notas adicionales 

## Referencias 
