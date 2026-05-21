## Descripción

- In RSA d is a lot bigger than e, why don't we use d to encrypt instead of e?
## Solución

- nos conectamos al servidor mediante nc para conseguir el texto cifrado (e), el módulo (n) y el exponente público gigante
- clonamos el repositorio de RsaCtfTool en tu máquina desde GitHub
- instalamos la herramienta directamente en el sistema usando el gestor de paquetes de Python (pip3 install)
- corrimos el comando de RsaCtfTool pasándole los tres números obtenidos y especificando el uso del ataque de Wiener (--attack wiener) junto con el comando de descifrado (--decrypt) para revelar la bandera final
## Notas adicionales 

## Referencias 