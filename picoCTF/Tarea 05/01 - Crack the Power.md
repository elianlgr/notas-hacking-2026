## Descripción

- We received an encrypted message. The modulus is built from primes large enough that factoring them isn’t an option, at least not today. See if you can make sense of the numbers and reveal the flag
## Solución

- Analicé los valores proporcionados en el reto de criptografía RSA y noté que el exponente era demasiado pequeño (e = 20).
    
- Deduje que el mensaje cifrado nunca excedió el valor del módulo (n), por lo que la encriptación era vulnerable a un ataque directo de raíz entera.
    
- Creé un script en Python llamado solve.py para calcular la raíz 20 del texto cifrado (c) utilizando un método de búsqueda binaria.
    
- Ejecuté el comando python3 solve.py, lo cual decodificó el número gigante de vuelta a su formato de texto original.
## Notas adicionales 

## Referencias 