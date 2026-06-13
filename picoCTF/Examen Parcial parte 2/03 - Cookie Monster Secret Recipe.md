## Descripción

- Cookie Monster has hidden his top-secret cookie recipe somewhere on his website. As an aspiring cookie detective, your mission is to uncover this delectable secret. Can you outsmart Cookie Monster and find the hidden recipe?
## Solución

- Ejecuté una petición POST al servidor usando la herramienta curl para simular un inicio de sesión.
    
- Incluí un parámetro en el comando para que la terminal me mostrara las cabeceras HTTP que devuelve el servidor.
    
- Analicé la respuesta de las cabeceras y encontré una cookie generada por el sistema llamada secret_recipe.
    
- Identifiqué que el valor de la cookie estaba codificado en formato Base64 debido a la longitud y al tipo de caracteres.
    
- Noté que los caracteres finales de la cadena estaban codificados para URL, así que copié el texto y cambié manualmente los símbolos de porcentaje por signos de igual para arreglar la sintaxis.
    
- Imprimí la cadena limpia en la terminal conectándola directamente con el comando de decodificación base64 de Linux.
    
- El sistema procesó la cadena y me reveló la bandera
## Notas adicionales 

## Referencias 
