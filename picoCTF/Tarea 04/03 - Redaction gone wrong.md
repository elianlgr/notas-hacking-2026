## Descripción

- This report has some critical data in it, some of which have been redacted correctly, while some were not. Can you find an important key that was not redacted properly?
## Solución

- Descargué el documento Financial_Report_for_ABC_Labs.pdf.
    
- Instalé la herramienta para extraer texto ejecutando sudo apt install poppler-utils.
    
- Usé el comando pdftotext Financial_Report_for_ABC_Labs.pdf - | grep pico para sacar la información que estaba escondida debajo de los cuadros negros.
## Notas adicionales 

## Referencias