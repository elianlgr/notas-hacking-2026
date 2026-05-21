## Descripción

- We found this file. Recover the flag.
- el reto nos da un archivo para descargar y poder resolver el reto
- parece ser que este archivo esta corrupto 
## Solución

- descargamos el archivo usando wget 
- aplicamos los comando xxd y head
- usamos la herramienta hexeditor para cambiar algunos valores en hexadecimal, aunque hayamos hecho estos cambios y ya se pueda abrir el archivo aun hay fallos en el que se tendrán que corregir
- instalamos un herramienta llamada pngcheck, al aplicar "pngchek -v" nos marca un error de redundancia cíclica
- volvemos a la herramienta hexeditor a corregir los chunck ya que la imagen es demasiado grande 
## Notas adicionales 

## Referencias 