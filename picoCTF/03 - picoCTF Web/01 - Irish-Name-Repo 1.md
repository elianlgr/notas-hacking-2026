## Descripción

- Do you think you can log us in? Try to see if you can login!
## Solución

- Identifiqué que el formulario de inicio de sesión era vulnerable a inyección SQL.
    
- Decidí explotarlo directamente desde la terminal utilizando la herramienta curl.
    
- Utilicé el payload admin' -- en el campo de usuario para forzar el acceso con esa cuenta interna.
    
- Envié un texto cualquiera como contraseña, ya que la inyección anulaba la validación de la misma en la base de datos.
    
- Incluí el parámetro de depuración en el comando para poder ver la consulta SQL procesada por el servidor.
    
- Ejecuté la petición y extraje la bandera directamente de la respuesta en la consola.
## Notas adicionales 

## Referencias 
