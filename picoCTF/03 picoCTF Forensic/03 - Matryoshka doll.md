## Descripción

- Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What's the final one?
- parece ser que hay archivos ocultos dentro de esa imagen
## Solución

- descargamos la imagen con wget 
- usamos la herramienta binwalk en la imagen para ver que hay en ella 
- extraemos los archivos que nos aparecieron con la función -e y se crea una subcarpeta
- entramos a la carpeta creada y hay una nuevamente
- encontramos la imagen a la que también le aplicamos un binwalk 
- nuevamente hay una carpeta, repetiremos este proceso hasta que encontremos la bandera 
- después de repetir el proceso varias veces encontramos la bandera en un archivo .txt
## Notas adicionales 

## Referencias