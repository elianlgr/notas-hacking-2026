## Descripción

- Our server seems to be leaking pieces of a secret flag in its logs. The parts are scattered and sometimes repeated. Can you reconstruct the original flag?
## Solución

- Ejecuté el comando grep -i flag server.log para filtrar el contenido del archivo de registros y mostrar únicamente las líneas relevantes.
    
- Analicé la salida en la terminal, identificando que la información de la bandera estaba dividida en cuatro fragmentos distintos que se repetían en diferentes marcas de tiempo.
    
- Extraje los fragmentos únicos picoCTF{us3_, y0urlinux_, sk1lls_ y cedfa5fb} descartando las líneas duplicadas.
    
- Reconstruí la cadena de texto uniéndolos en su orden lógico para obtener y capturar la bandera final exitosamente.
## Notas adicionales 

![[Pasted image 20260614113652.png]]
## Referencias 
