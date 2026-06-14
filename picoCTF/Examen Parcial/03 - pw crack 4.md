## Descripción

- Can you crack the password to get the flag?
- Download the password checker here and you'll need the encrypted flag and the hash in the same directory too.
- There are 100 potential passwords with only 1 being correct. You can find these by examining the password checker script.
## Solución

- ejecute el comando wget usando los enlaces del reto para descargar los tres archivos requeridos que son level4.flag.txt.enc level4.hash.bin y level4.py
- use el comando ls para confirmar que los tres archivos ya se encuentran guardados en el directorio actual
- ejecute el comando iterativo for pass in $(cat level4.py); do echo $pass | tr -d ,[] | python3 level4.py; done | grep pico para extraer las contraseñas del script limpiarlas y probarlas todas automaticamente
## Notas adicionales 

![[Pasted image 20260614113612.png]]
## Referencias 
