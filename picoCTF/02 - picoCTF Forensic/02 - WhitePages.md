## Descripción

- I stopped using YellowPages and moved onto WhitePages... but the page they gave me is all blank!
- nos da un archivo txt para descargar y empezar con la búsqueda 
## Solución

- descargamos el archivo con wget 
- aplicamos el comando cat para ver que hay dentro del archivo, aparentemente no hay nada dentro
- aplicamos el comando wc para ver el numero de caracteres, líneas o palabras 
- al aplicarle file nos dice que es un archivo de tipo unicode
- usamos el comando xxd "nombre del archivo" | head nos aparecen varios numeros donde algunos son de lenguaje unicod y otros de código hexadecimal. ambos son espacios en blanco 
- usamos una herramienta de python llamada pwntools que nos ayudara a descifrar el contenido del archivo 
- usamos este bloque de codigo para que nos de la bandera 
	from pwn import*

	file = open('whitepages.txt','rb')
	data = bytearray(file.read())
	data = data.replace(b'\xe2\x80\x83',b'0')
	data = data.replace(b'\x20',b'1')         
	data = data.decode('ascii')
	data = unbits(data)
	print(data)

## Notas adicionales 

## Referencias 