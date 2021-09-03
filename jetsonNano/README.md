# Entrenamiento de modelos de detección con PyTorch
Este entrenamiento está basado en el tutorial de [NVIDIA Jetson Hello AI World](https://github.com/dusty-nv/jetson-inference).

Este cuaderno de Jypiter se ha elaborado para entrenar modelos de detección utilizando PyTorch.

## Estructura de directorios  
* pytorch-ssd: Framework de PyTorch con todas las funciones necesarias  
* [Test](Test/): Imágenes y vídeos para pruebas de inferencia  
	* [src](Test/src/): Archivos de origen  
	* [dst](Test/dst/): Archivos de destino  
* [model](model/): checkpoints del modelo y modelo.onnx  
* [data](data/): Dataset con la estructura necesaria que requiere PyTorch
  
