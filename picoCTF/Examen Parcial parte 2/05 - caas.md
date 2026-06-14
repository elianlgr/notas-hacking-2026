## Descripción

- Now presenting
## Solución

- Analicé el código fuente del archivo index.js y descubrí que la aplicación era vulnerable a una inyección de comandos porque pasaba el texto ingresado directamente a la terminal del servidor sin revisarlo.
    
- Para listar los archivos del servidor, abrí la terminal y envié una petición web inyectando el comando ls después de un punto y coma usando: curl "[https://caas.mars.picoctf.net/cowsay/prueba;ls](https://www.google.com/search?q=https://caas.mars.picoctf.net/cowsay/prueba%3Bls)"
    
- En la respuesta que me devolvió el servidor identifiqué el nombre del archivo que contenía la bandera, el cual era falg.txt.
    
- Para extraer la bandera final, envié una segunda petición inyectando el comando cat para leer el contenido de ese archivo, usando la codificación de URL para los espacios, ejecutando: curl "[https://caas.mars.picoctf.net/cowsay/prueba;cat%20falg.txt](https://www.google.com/search?q=https%3A%2F%2Fcaas.mars.picoctf.net%2Fcowsay%2Fprueba%3Bcat%2520falg.txt)"
## Notas adicionales 

![[Pasted image 20260614115314.png]]
## Referencias 
