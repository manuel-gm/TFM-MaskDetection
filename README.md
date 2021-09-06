# Sensor para detectar el uso de mascarillas en entornos COVID
Trabajo de Fin de Máster

Máster en Nuevas Tecnologías Electrónicas y Fotónicas.  
Universidad Complutense de Madrid. Curso 2020-21
### Autor: Manuel Gómez Moreno
### Supervisor: Dr. Carlos García Sánchez

# Resumen
La visión artificial es una de las ramas de la ciencia de la computación que
 más se ha desarrollado en los últimos años gracias a la aparición de las 
 redes neuronales convolucionales. Debido a la actual pandemia de COVID-19
 y el extendido uso de mascarillas para frenar su propagación, la detección
 por medio de estos modelos se ha convertido en un tema de gran investigación. 
 El objetivo de este trabajo es entrenar, analizar y comparar diferentes modelos
 de aprendizaje profundo que permitan detectar personas con mascarilla, sin 
 mascarilla y con mascarilla mal puesta. Dentro de los modelos de detección 
 se han estudiado tres modelos de la familia EfficientDet con diferentes
 tamaños junto con un SSD MobileNet v1. Se han logrado detecciones con 
 una precisión cercana al 80%. Además, un modelo como este último se ha 
 inferido en la NVIDIA Jetson Nano 2GB para comprobar la viabilidad de un 
 sistema de detección en tiempo real, logrando un procesamiento con una velocidad
 de $34$ fotogramas por segundo. Finalmente, se ha investigado una alternativa a 
 los modelos detectores que emplea BodyPix de Google para segmentar 
 caras que después se clasifican con un MobileNet v2. Todos los 
 programas desarrollados han sido subidos a un repositorio de GitHub bajo la 
 licencia MIT para ser utilizados por la comunidad.

## Índice  
* [Evaluación de modelos de detección](detection-models/)  
* [Inferencia en Jetson Nano 2GB](jetsonNano/)  
* [BodyPix + Clasificación MobileNet v2](classification-models/)  

## Notas  
* Todos los cuadernos de Jupyter están pesados para ejecutarse desde Google Colab 
utilizando la aceleración por GPU.

