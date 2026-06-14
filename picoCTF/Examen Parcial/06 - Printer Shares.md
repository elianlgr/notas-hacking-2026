## Descripción

- Oops! Someone accidentally sent an important file to a network printer—can you retrieve it from the print server?
## Solución

- Ejecute el comando smbclient -L //mysterious-sea.picoctf.net -p 63623 -N para listar las carpetas expuestas en el servidor.
    
- Identifique en la tabla resultante el nombre del recurso compartido, que generalmente se llama shares.
    
- Me conecte a ese recurso especifico ingresando smbclient //mysterious-sea.picoctf.net/shares -p 63623 -N en tu terminal.
    
- Escribí ls una vez dentro de la conexion para listar los archivos disponibles y ubicar el documento de texto.
    
- Escribí get flag.txt para descargar el documento desde la impresora a tu computadora local.
    
- Escribí exit para terminar la conexion con el servidor.
    
- Escribí cat flag.txt en tu terminal para leer el contenido del archivo descargado y obtener la respuesta.
## Notas adicionales 

![[Pasted image 20260614113812.png]]
## Referencias 
