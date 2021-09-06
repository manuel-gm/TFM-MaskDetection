# Detección mediante la combinación de segmentación y clasificación
Esta parte consiste en la detección de msacarillas mediante la segmentación de la cara con el
modelo BodyPix de Google y la clasificación de un modelo MobileNet v2 entrenado en TensorFlow 2.

El cuaderno de Jupyter [training.ipynb](training.ipynb) es el encargado de entrenar el modelo
de clasificación. Está a su vez basado en este otro [cuaderno](https://github.com/aryan109/medium/blob/master/Custom_Image_Classification/Custom_image_clasification.ipynb).

El cuaderno [inference.ipynb](inference.ipynb) contiene el código para realizar la detección
conjunta de ambos modelos.

## Estructura de directorios  
* [Test](Test/): Imágenes y vídeos para pruebas de inferencia  
	* [src](Test/src/): Archivos de origen  
	* [dst](Test/dst/): Archivos de destino  
	* [mask](Test/mask/): Máscaras calculadas con BodyPix  
* [dataset](dataset/): Dataset de clasificación  
* [images](images/): Dataset de detección utilizado para crear el de clasificación  
* [saved models](saved_models/): Modelo de clasificación entrenado  

