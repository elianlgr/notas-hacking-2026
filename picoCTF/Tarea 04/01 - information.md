## Descripción

- Files can always be changed in a secret way. Can you find the flag?
## Solución

- Descargué el archivo de evidencia proporcionado por el reto, el cual era una imagen con el nombre cat.jpg.
    
- Abrí mi terminal de comandos y utilicé la herramienta exiftool ejecutando el comando exiftool cat.jpg para extraer e inspeccionar los metadatos del archivo.
    
- Revisé línea por línea la información arrojada por la herramienta y noté que el campo llamado License contenía una cadena de texto anómala que no correspondía a una licencia estándar.
    
- Identifiqué que esa cadena de texto extraña estaba codificada en formato base64.
    
- Procedí a decodificar la cadena directamente en mi terminal usando el comando echo seguido del texto y usando una tubería hacia base64 -d para revelar su contenido.
## Notas adicionales 

## Referencias