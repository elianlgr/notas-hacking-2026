## Descripción

- Can you reverse a series of Linux text transformations to recover the original flag?
## Solución

- Me conecté a la instancia del servidor ejecutando: nc foggy-cliff.picoctf.net 57195
    
- Revertí la codificación del texto ingresando: base64 -d
    
- Restauré el orden original de la cadena de caracteres usando: rev
    
- Reemplacé los guiones por guiones bajos mediante: tr '-' '_'
    
- Sustituí los paréntesis por llaves para arreglar el formato con: tr '()' '{}'
    
- Revertí el cifrado ROT13 de las letras aplicando: tr 'A-Za-z' 'N-ZA-Mn-za-m'
## Notas adicionales 

![[Pasted image 20260614113844.png]]
## Referencias 
