## Descripción

- Want to play a game? As you use more of the shell, you might be interested in how they work! Binary search is a classic algorithm used to quickly find an item in a sorted list. Can you find the flag? You'll have 1000 possibilities and only 10 guesses.
- Cyber security often has a huge amount of data to look through - from logs, vulnerability reports, and forensics. Practicing the fundamentals manually might help you in the future when you have to write your own tools!
## Solución

- Inicié la instancia del reto en la plataforma para obtener las credenciales de conexión.
    
- Me conecté al servidor mediante SSH utilizando el comando: ssh -p 58387 ctf-player@atlas.picoctf.net
    
- Acepté la huella de seguridad y autentiqué la sesión con la contraseña proporcionada.
    
- Ejecuté el script del juego y comencé a aplicar el algoritmo de búsqueda binaria.
    
- Realicé los intentos numéricos calculando el punto medio exacto del rango posible en cada paso, basándome en las respuestas "Higher" y "Lower" del sistema para reducir las opciones.
    
- Identifiqué el número secreto tras aplicar el método de división constante, lo que permitió que la consola mostrara la bandera del reto.
## Notas adicionales 

## Referencias 