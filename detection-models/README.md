# Entrenamiento de modelos de detección
Este entrenamiento está basado en el tutorial de [Renu Khandelwal](https://medium.com/analytics-vidhya/tensorflow-2-object-detection-api-using-custom-dataset-745f30278446).

Este cuaderno de Jypiter se ha elaborado para entrenar modelos de detección utilizando TensorFlow 2 Object Detection API.
Los modelos deben ser descargados desde el [model zoo de la API](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md). La evaluación de los modelos se realiza con el script de [Padilla et al.](https://github.com/rafaelpadilla/Object-Detection-Metrics)

## Estructura de directorios
*[Workspace](Workspace/): Carpeta que almacena todo lo relativo al entrenamiento  
	* [annotations](Workspace/annotations/): archivos record y label_map  
	* [images](Workspace/images/): datasets de entrenamiento y evaluación  
	* [pretrained_models](Workspace/pretrained_models/): modelos preentrenados  
	* [models](Workspace/models): checkpoints de los modelos durante el entrenamiento  
	* [exported_models](Workspace/exported_models/): modelos entrenados  
* [Test](Test/): Imágenes y vídeos para pruebas de inferencia  
	* [src](Test/src/): Archivos de origen  
	* [dst](Test/dst/): Archivos de destino  
* [Evaluation](Evaluation/): bounding boxes, ground truth y métricas de error  
	* [detection_bbox](Evaluation/detection_bbox/)  
	* [ground_truth](Evaluation/ground_truth/)  
	* [metrics](Evaluation/metrics/)  
  
