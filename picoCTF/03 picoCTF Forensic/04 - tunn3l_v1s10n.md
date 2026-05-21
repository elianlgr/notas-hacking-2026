## Descripción

- We found this file. Recover the flag.
## Solución

- descargue el archivo sin extension y descubri que en realidad era un archivo de imagen bmp corrupto
- al intentar abrir la imagen el sistema me daba error asi que la abri con un editor hexadecimal para analizar su cabecera
- note que los valores del offset de los pixeles y del tamaño de la cabecera estaban alterados intencionalmente con el valor ba d0
- repare esos valores sobreescribiendolos con 36 00 00 00 y 28 00 00 00 que son los valores estandar para que funcione un bmp
- al guardar y abrir la imagen me salio un mensaje falso lo que me hizo pensar en el titulo del reto vision de tunel
- volvi al editor hexadecimal y modifique el valor de la altura de la imagen en el offset 0x16 cambiandolo de 32 01 a 32 03 para forzar un lienzo mas alto
- guarde los cambios abri la imagen de nuevo y esta vez revelo la bandera real que estaba escondida en la parte superior del archivo
## Notas adicionales 

## Referencias 