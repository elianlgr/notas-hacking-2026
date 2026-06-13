## Descripción

- Someone's commits seems to be preventing the program from working. Who is it?
## Solución

- Descomprimí el archivo challenge.zip en la terminal utilizando el comando: unzip challenge.zip
    
- Ingresé a la carpeta del proyecto ejecutando el comando: cd drop-in
    
- Añadí la excepción de seguridad en Git para el directorio actual con el comando: git config --global --add safe.directory /home/kali/Hacking/Tarea1/drop-in
    
- Revisé el historial de cambios del repositorio filtrando la salida para encontrar la bandera directamente con el comando: git log | grep "picoCTF"
## Notas adicionales 

## Referencias 