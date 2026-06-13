## Descripción

- We found a leak of a blackmarket website's login credentials. Can you find the password of the user `cultiris` and successfully decrypt it?
- The first user in `usernames.txt` corresponds to the first password in `passwords.txt`. The second user corresponds to the second password, and so on.
## Solución

 Descargué el archivo comprimido leak.tar que contenía los datos filtrados.
    
- Descomprimí el archivo usando el comando tar -xf leak.tar y entré a la carpeta leak.
    
- Usé el comando grep -n "cultiris" usernames.txt para encontrar que el usuario estaba en la línea 378.
    
- Ejecuté el comando sed -n '378p' passwords.txt para extraer la contraseña cifrada correspondiente a esa misma línea.
    
- Copié la cadena obtenida y la descifré usando el comando con tr para aplicar la rotación de caracteres de ROT13.
## Notas adicionales 

## Referencias 