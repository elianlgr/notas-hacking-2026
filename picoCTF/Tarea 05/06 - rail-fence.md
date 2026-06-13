## Descripción

- A type of transposition cipher is the rail fence cipher, which is described Here is one such cipher encrypted using the rail fence with 4 rails. Can you decrypt it?
- Put the decoded message in the picoCTF flag format, `picoCTF{decoded_message}`.
## Solución

- Leí el contenido del archivo message.txt usando el comando cat message.txt en la terminal.
    
- Extraje la cadena de texto cifrada: Ta-7N6DDDhlg:W3D_H3C31N__0D3ef sHR053F38N43D0F i33___NA.
    
- Identifiqué que el texto estaba protegido con un cifrado de transposición Rail Fence usando 4 rieles, basándome en la descripción del reto.
    
- Ingresé el texto cifrado en la herramienta CyberChef utilizando la operación Rail Fence Cipher Decode con el parámetro de clave ajustado a 4.
## Notas adicionales 

## Referencias 