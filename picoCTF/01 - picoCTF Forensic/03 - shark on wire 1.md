## Descripción

- We found this packet capture. Recover the flag.
- nos da un archivo para descargar y que podamos empezar la búsqueda de la bandera 
## Solución

- descargamos el archivo 
- después de descargar el archivo usaremos la herramienta "wireshark" que nos permite vaciar y analizar trafico de red o navegar sobre una captura de paquetes previamente realizada 
- abrimos la carpeta y el archivo que hemos descargado previamente 
- nos aparece el numero de paquete, la hora generada del paquete, la IP de donde se genero el paquete y la IP del destino del paquete, el protocolo, la longitud del paquete y su información 
- empezamos la búsqueda por un paquete UDP y usamos la función de seguir el stream de paquetes 
- ahora simplemente buscamos stream por stream hasta encontrar la bandera 
## Notas adicionales 

## Referencias 