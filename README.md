# Clasificación de Comidas bolivianas
by Daniel Mancilla

Se trata de un clasificador en tiempo real de comidas bolivianas. Puede utilizarse en el celular, solo apunta con la cámara al plato para saber el nombre, lo hace todo en el explorador utilizando Tensorflow.js, en base aun modelo entrenado en Python con Tensorflow

## Datos del modelo
 El modelo de IA de esta web fue entrenado con un dataset personalizado y creado para la materia de Inteligencia artificial I

## Cómo utilizarlo

### Descargar el repositorio
Descarga el repositorio donde gustes en tu computadora

### Inicia un servidor en la carpeta
Este proyecto utiliza un modelo de Tensorflow.js, el cual para cargarse requiere que el acceso sea por medio de http/https.
Para eso puedes usar cualquier servidor, pero aquí hay una forma de hacerlo:
- Descarga Python en tu computadora
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste el repositorio
- Ejecuta el comando `python -m http.server 8000`
- Abre un explorador y ve a http://localhost:8000

### Utilizarlo en un celular
Si quieres abrirlo en tu celular, no se puede solo poner la IP local de tu computadora y el puerto, ya que para usar la cámara se requiere HTTPS. Puedes hacer un túnel de HTTPS siguiendo los siguientes pasos
- Descarga ngrok en tu computadora, y descomprímelo
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste ngrok
- Ejecuta el comando `ngrok http 8000`
- Es importante tener ambos activos: El servidor de python, y el túnel de ngrok
- En la línea de comandos aparecerá un enlace HTTPS. Puedes entrar ahí con tu celular, no importa si no estás en la red local.
- El túnel expira después de 2 horas creo, en dado caso solo reinicias ngrok
- Abre un explorador en tu celular y ve al enlace HTTPS indicado

### Uso
Puedes dar clic en el botón de "Cambiar camara" para utilizar la cámara delantera o trasera del celular. Solo apunta la cámara al plato, y abajo te aparecerá la predicción. Tampoco es el clasificador del futuro entonces si no clasifica perfecto, oops.

Puedes capturar la imagen con la cámara para que el modelo te de una prediccion

puedes subir una imagen desde tus archivos para que el modelo te de una prediccion

## Con que datos fue entrenado
 - Se creo un dataset personalizado con fotos de las comidas típicas por departamento
 - solo fue entrenado con 29 platos típicos

## Links
### link al código en Python del modelo
 - https://github.com/danimtx/Modelo-IA-Prediccion-Comidas-bolivianas.git
### link al dataset de comidas en drive
 - El dataset contiene fotos de 29 platos típicos
 - 1000 fotografías por cada plato
 - Total 29 000 fotografias
 - https://drive.google.com/uc?export=download&id=1UPg5K2Q-w_ImJ60FtDAejuFgQO66tUyp

### ¿quieres colaborar o necesitas otro dataset referente a Bolvia?
 - hay otros datasets referentes a la cultura boliviana creados por los estudiantes de esta materia
 - si quieres colaborar visita este repositorio
 - https://github.com/upds-estudiantes/datasets-bolivia.git

## Creditos
 - El diseño de la pagina web fue copiada del canal de YouTube [Ringa Tech](https://youtube.com/RingaTech)
 - Se añadió la función se sacar foto y subir foto
 - personas que colaboraron a conseguir las fotos de los platos para el dataset

 - Daniel mancilla 
 - Victor taja 
 - Victor Saldaña
 - Hugo Acosta
 - Sebastián Zambrana
 - Nick Torrez
 - Victor Tejerina 
 - Jair amerani 
 - Erick