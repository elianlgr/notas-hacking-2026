## Descripción

- We found this weird message being passed around on the servers, we think we have a working decryption scheme. Download the message here.
- Take each number mod 37 and map it to the following character set: 0-25 is the alphabet (uppercase), 26-35 are the decimal digits, and 36 is an underscore. Wrap your decrypted message in the picoCTF flag format (i.e. `picoCTF{decrypted_message}`)
## Solución

- descargar el archivo de texto que contiene el mensaje cifrado.
- crear un script de Python en la misma carpeta donde guardaste el archivo descargado.
- programar el script para que lea los numeros del archivo y calcule el modulo 37 de cada uno.
- incluir en el script las condiciones para convertir esos resultados a letras mayusculas, numeros o guion bajo.
- ejecutar el codigo en la terminal para obtener el texto descifrado.
- envolver ese texto final con el formato de la bandera para poder enviarla.
## Notas adicionales 

## Referencias 