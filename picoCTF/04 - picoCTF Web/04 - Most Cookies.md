## Descripción

- Alright, enough of using my own encryption. Flask session cookies should be plenty secure!
## Solución

- dentifiqué que el reto utilizaba cookies de sesión de Flask, las cuales están firmadas criptográficamente pero no cifradas, permitiendo decodificarlas y leer su contenido.
    
- Obtuve la cookie de sesión inicial realizando una petición HTTP básica a la página web del reto.
    
- Creé un diccionario de palabras (`wordlist.txt`) que contenía los nombres de galletas extraídos previamente del código fuente original del servidor.
    
- Ejecuté la herramienta `flask-unsign` pasándole el token puro de la cookie decodificada y el diccionario de palabras para realizar un ataque de fuerza bruta, descubriendo que la clave secreta (`SECRET_KEY`) del servidor era `oatmeal raisin`.
    
- Utilicé nuevamente `flask-unsign` con el parámetro `--sign` para forjar y firmar una nueva cookie de sesión con privilegios elevados (`{'very_auth': 'admin'}`) utilizando la clave descubierta.
    
- Realicé una petición HTTP final hacia la ruta `/display` utilizando `curl`, inyectando mi cookie falsificada correctamente estructurada en las cabeceras (`-H "Cookie: session=..."`), lo que validó mi sesión como administrador y me reveló la bandera.
## Notas adicionales 

## Referencias 
