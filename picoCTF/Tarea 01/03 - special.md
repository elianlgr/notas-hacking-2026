## Descripción

- Don't power users get tired of making spelling mistakes in the shell? Not anymore! Enter Special, the Spell Checked Interface for Affecting Linux. Now, every word is properly spelled and capitalized... automatically and behind-the-scenes! Be the first to test Special in beta, and feel free to tell us all about how Special streamlines every development process that you face. When your co-workers see your amazing shell interface, just tell them: That's Special
## Solución

- Iniciar sesión en el servidor remoto por medio de SSH utilizando el comando: ssh -p 63076 ctf-player@saturn.picoctf.net
    
- Ingresar la contraseña proporcionada para acceder a la consola del entorno restringido.
    
- Evadir el corrector ortográfico y la restricción de rutas absolutas del sistema empleando rutas relativas que inician con un punto.
    
- Listar los directorios y archivos del sistema ejecutando el comando: ../../bin/ls
    
- Identificar la carpeta llamada blargh entre los resultados mostrados en la consola.
    
- Leer directamente el archivo de la bandera ejecutando el comando: ../../bin/cat ./blargh/flag.txt
## Notas adicionales 

## Referencias 