## Descripción

- Who doesn't love cookies? Try to figure out the best one.
## Solución

- Analicé el sitio web del reto y descubrí que el contenido de la página cambiaba dependiendo del valor numérico asignado a la cookie `name`.
    
- Decidí automatizar la búsqueda de la cookie correcta directamente desde mi terminal para no hacerlo manualmente.
    
- Ejecuté un bucle en bash utilizando el comando `for` iterando del 1 al 30, y combinándolo con `curl` para inyectar cada valor en las peticiones HTTP al servidor.
    
- Añadí una tubería hacia `grep "picoCTF{"` para filtrar la salida y encontrar exactamente la línea con el formato correcto.
## Notas adicionales 

## Referencias 