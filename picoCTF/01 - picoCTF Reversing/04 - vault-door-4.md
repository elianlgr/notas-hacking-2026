## Descripción

- This vault uses ASCII encoding for the password.
## Solución
- descargué el archivo vaultdoor4.java y examiné su código fuente en la terminal
- observé que la contraseña estaba almacenada en un arreglo de bytes utilizando diferentes bases numéricas
- identifiqué que la primera fila estaba en decimal, la segunda en hexadecimal, la tercera en octal y la cuarta como caracteres de texto
- convertí cada uno de los valores numéricos a su representación en texto normal utilizando la tabla ascii
- uní todos los caracteres decodificados en orden para formar la cadena completa
## Notas adicionales 

## Referencias 