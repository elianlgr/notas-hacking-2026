## Descripción

- todo indica que tenemos que encontrar la bandera dentro de los metadatos de la imagen, pero hay un problemas, no nos deja descargar la imagen como normalmente se hace 
## Solución

- abrimos el enlace que nos da al iniciar la instancia, 
- usamos la herramienta inspector para acceder a su codigo 
- vamos la parte de sources y nos vamos al archivo concat.png (ya tenemos manera de descargar la imagen)
- descargamos la imagen desde la terminal de kali con el comando wget 
- usamos el comando steghide extract -sf para extraer lo necesario ya que con solo usar el comando zsteg no era suficiente 
## Notas adicionales 

## Referencias 