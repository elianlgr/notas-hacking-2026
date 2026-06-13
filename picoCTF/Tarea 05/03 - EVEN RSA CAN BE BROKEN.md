## Descripción

- This service provides you an encrypted flag. Can you decrypt it with just N & e?
## Solución

- Ingresé el valor público de $N$ en la base de datos factordb.com y descubrí una vulnerabilidad crítica en la generación de las llaves: el módulo $N$ era un número par.
    
- Identifiqué los factores primos correspondientes, siendo el primero $p = 2$ y el segundo ($q$) el resultado directo de la división de $N$ a la mitad.
    
- Integré estos dos factores en el script de descifrado en Python para reconstruir la llave privada ($d$).
    
- Ejecuté el script, logrando descifrar el texto original para obtener la bandera y completar la prueba con éxito.
## Notas adicionales 

## Referencias 