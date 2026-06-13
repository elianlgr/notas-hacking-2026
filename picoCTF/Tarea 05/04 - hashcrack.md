## Descripción

- A company stored a secret message on a server which got breached due to the admin using weakly hashed passwords. Can you gain access to the secret stored within the server?
## Solución

- Extraje el primer hash (MD5) e intenté realizar un ataque de diccionario, pero descubrí que el archivo `rockyou.txt` estaba comprimido por defecto en mi sistema, así que lo extraje usando `sudo gzip -d /usr/share/wordlists/rockyou.txt.gz`.
    
- Descifré el primer hash usando John the Ripper forzando el formato (`john --format=Raw-MD5 --wordlist=/usr/share/wordlists/rockyou.txt hash.txt`) y obtuve la primera contraseña.
    
- Al ingresar la clave, el servidor me botó de la conexión, por lo que tuve que reconectarme. Esta vez me entregó un segundo hash más largo (40 caracteres), el cual identifiqué como SHA-1.
    
- Ajusté el comando de la herramienta al nuevo formato (`--format=Raw-SHA1`), descifré la segunda contraseña y la ingresé al sistema.
    
- Finalmente, el servidor me arrojó un tercer hash de 64 caracteres. Lo clasifiqué como SHA-256, repetí el proceso de descifrado con el formato correspondiente (`--format=Raw-SHA256`) y extraje la última contraseña.
    
- Ingresé la tercera contraseña en el servidor, completando exitosamente todas las fases de autenticación
## Notas adicionales 

## Referencias 