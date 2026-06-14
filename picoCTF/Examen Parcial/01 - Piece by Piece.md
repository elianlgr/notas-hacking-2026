## Descripción

- After logging in, you will find multiple file parts in your home directory. These parts need to be combined and extracted to reveal the flag..
## Solución

- Primero, abrimos nuestra terminal y nos conectamos al servidor usando la herramienta SSH, especificando el puerto 53349, el usuario ctf-player y la dirección dolphin-cove.picoctf.net.
    
- Cuando el sistema nos solicitó la contraseña, introdujimos f3b61b38, la cual estaba indicada directamente en la descripción del problema.
    
- Una vez dentro del servidor, utilizamos el comando para listar los archivos y comprobamos que en nuestro directorio había múltiples piezas de un archivo dividido.
    
- A continuación, usamos el comando de lectura y concatenación junto con un comodín asterisco para unir todas esas partes en el orden correcto, guardando el resultado en un nuevo archivo unificado.
    
- Como el archivo que reconstruimos era un archivo comprimido, ejecutamos la herramienta correspondiente para extraer todo su contenido en ese mismo directorio.
    
- Finalmente, leímos el texto del archivo extraído para revelar la bandera completa y la copiamos para enviarla en la página de picoCTF.
## Notas adicionales 

![[Pasted image 20260614115056.png]]
## Referencias 