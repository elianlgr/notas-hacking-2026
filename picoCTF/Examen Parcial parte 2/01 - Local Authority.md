## Descripción

- Can you get the flag?
## Solución

- Ejecuté el comando curl -s [http://saturn.picoctf.net:65093/secure.js](https://www.google.com/search?q=http://saturn.picoctf.net:65093/secure.js) para inspeccionar el archivo de validación del sitio.
    
- Hice un análisis del código JavaScript que me devolvió la consola.
    
- Noté que dentro de la función checkPassword ya venían declaradas las variables en texto plano, obteniendo así el usuario admin y la contraseña strongPassword098765.
    
- Ingresé a la página web del reto en mi navegador.
    
- Logueé esas mismas credenciales en el formulario de inicio de sesión.
    
- El sistema me dio acceso y me mostró la bandera en la pantalla.
## Notas adicionales 

## Referencias 
