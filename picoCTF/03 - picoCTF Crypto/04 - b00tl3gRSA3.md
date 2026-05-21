## Descripción

- Why use p and q when I can use more?
## Solución

- nos conectamos al servidor mediante nc para conseguir el texto cifrado (c), el módulo débil compuesto por múltiples primos (n) y el exponente público (e)
- copiamos el número gigante n y lo procesamos en la calculadora criptográfica en línea de Alpertron, la cual calculó los factores y nos entregó directamente el Totient de Euler (phi(N))
- escribimos un pequeño script en Python y le introdujimos los cuatro valores exactos que ya teníamos (c, n, e y el phi(N) sin espacios)
- corrimos el script en la terminal, el cual calculó la clave privada (d) de forma instantánea usando el Totient y descifró el mensaje original para revelar la bandera
## Notas adicionales 

## Referencias 