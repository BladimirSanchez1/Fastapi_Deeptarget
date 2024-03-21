# FastApi DeepTarget
Este codigo lo que hace es:
1. Genera el audio wav del video completo
2. Genera el transcript con whisper en un archivo JSON
3. Genera un clip de 5 seg al detectar una cara por ese tiempo
4. Genera el audio wav del clip de 5 seg limpio de sonidos de fondo

## Detalles
Este codigo fue probado con el postman para poder simular una pagina web que mandaba videos para poder ejecutar el proceso del codigo.
