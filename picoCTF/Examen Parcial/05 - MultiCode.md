## Descripción

- We intercepted a suspiciously encoded message, but it’s clearly hiding a flag. No encryption, just multiple layers of obfuscation. Can you peel back the layers and reveal the truth?
## Solución

- base64 -d: Quita la primera capa Base64.
    
- xxd -r -p: Convierte el texto hexadecimal resultante a caracteres normales ASCII.
    
- python3 -c ...: Limpia la codificacion URL convirtiendo los simbolos en las llaves del formato.
    
- tr a-zA-Z n-za-mN-ZA-M: Rota las letras 13 posiciones para traducir el formato oculto a la bandera final.
## Notas adicionales 

## Referencias 
