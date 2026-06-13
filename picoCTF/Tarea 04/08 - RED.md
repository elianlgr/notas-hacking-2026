## Descripción

- RED, RED, RED, RED
- Download the image
## Solución

- ejecuté el comando zsteg red.png para analizar las capas ocultas de la imagen.
    
- Revisé los resultados y encontré una cadena de texto codificada en Base64 en uno de los canales.
    
- Extraje la cadena y la decodifiqué ejecutando el comando echo seguido del texto y usando una tubería hacia base64 -d.
## Notas adicionales 

## Referencias