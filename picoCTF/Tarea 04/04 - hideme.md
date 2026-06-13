## Descripción

- Every file gets a flag.
- The SOC analyst saw one image been sent back and forth between two people. They decided to investigate and found out that there was more than what meets the eye
## Solución

- Descargué la imagen flag.png.
    
- Ejecuté el comando binwalk flag.png y descubrí que la imagen ocultaba un archivo ZIP.
    
- Usé el comando binwalk -e flag.png para extraer los archivos ocultos en una nueva carpeta.
    
- Navegué a la ruta flag.png.extracted/secret donde se extrajo el contenido.
    
- Abrí la imagen oculta que estaba ahí, leí la bandera y resolví el reto.
## Notas adicionales 

## Referencias