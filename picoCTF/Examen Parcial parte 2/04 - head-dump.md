## Descripción

- Welcome to the challenge! In this challenge, you will explore a web application and find an endpoint that exposes a file containing a hidden flag.
- The application is a simple blog website where you can read articles about various topics, including an article about API Documentation. Your goal is to explore the application and find the endpoint that generates files holding the server’s memory, where a secret flag is hidden.
## Solución

- Investigué los directorios del servidor y descubrí que la documentación de la API exponía una ruta vulnerable de diagnóstico.
    
- Utilicé el comando curl apuntando al endpoint oculto para descargar el volcado de memoria del servidor y lo guardé localmente como heapdump.txt.
    
- Comprendí que leer la memoria en crudo manualmente es ineficiente debido a la inmensa cantidad de datos que contiene el archivo.
    
- Utilicé el comando grep para filtrar el documento y buscar automáticamente el patrón de texto específico de la bandera.
## Notas adicionales 

## Referencias 
