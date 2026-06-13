## Descripción

- My team has been working very hard on new features for our flag printing program! I wonder how they'll work together?
## Solución

- Descomprimí el archivo challenge.zip en la terminal utilizando el comando: unzip challenge.zip
    
- Ingresé a la carpeta del proyecto ejecutando el comando: cd drop-in
    
- Añadí la excepción de seguridad en Git para el directorio actual con el comando: git config --global --add safe.directory /home/kali/Hacking/Tarea1/drop-in/drop-in/drop-in/drop-in
    
- Listé todas las ramas de desarrollo ocultas en el repositorio utilizando el comando: git branch -a
    
- Forcé el cambio a la primera rama de desarrollo para ignorar los conflictos de archivos locales ejecutando el comando: git checkout -f feature/part-1
    
- Leí el contenido del archivo principal para obtener el primer fragmento de la bandera usando el comando: cat flag.py
    
- Repetí el proceso de cambio de rama forzado y lectura de archivo para las ramas feature/part-2 y feature/part-3 para extraer los fragmentos restantes.
    
- Uní los tres fragmentos impresos en la consola para formar y registrar la bandera completa.
## Notas adicionales 

## Referencias 