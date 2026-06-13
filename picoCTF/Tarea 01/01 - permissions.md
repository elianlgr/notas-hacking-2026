## Descripción

- Can you read files in the root file?
## Solución

- Iniciar sesión en el servidor remoto por medio de SSH utilizando el comando: ssh -p 52275 picoplayer@saturn.picoctf.net
    
- Verificar los comandos que el usuario puede ejecutar con privilegios de administrador usando: sudo -l
    
- Identificar la vulnerabilidad en la configuración que permite ejecutar el programa /usr/bin/vi como root.
    
- Ejecutar el editor de texto con privilegios máximos mediante el comando: sudo vi
    
- Escapar hacia una terminal de comandos desde adentro del editor ingresando la secuencia: :!/bin/bash
    
- Cambiar al directorio del superusuario ejecutando el comando: cd /root
    
- Listar todos los archivos del directorio, incluyendo los ocultos, con el comando: ls -la
    
- Leer el archivo que contiene la bandera final usando el comando cat seguido del nombre del archivo.
## Notas adicionales 

## Referencias 