# MODELO_CLASIFICADOR_CARNE
MODELO DE CLASIFICADOR DE CARNES PYTHON 
## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)

### General Info
***
En este proyecto realizamos un modelo de clasificación de imágenes de tipos de Carnes utilizando la API Keras de tensor flow  para realizar machine learning 
Como primer paso se realizo la limpieza del Data set por mi parte  ELIMINE LAS CARPETAS QUE NO TENIAN IMAGENES CORRESPONDIENTE A LA CLASS_01 ya que no considere que se deba entrenar con una imagen y despues no se pueda validar porque no hay imagenes , tambien elimine imagenes que no tenian relacion con las gabetas vacias y solo confundirian a nuestro modelo buscando caracteristicas diferentes a las deseadas, 
escale las imagenes a 255y se creo un modelo secuencial utilizando capas convolucionales para el procesamiento de las imagenes y capas profundas para el entrenamiento y una capa de salida tipo SOFTMAX  

Se realizo muchas pruebas con diferentes calibraciones de tamaños de imagenes y tipos de optimizadores asi como epocas de entrenamiento hasta llegar a nuestro modelo final el cual esta adjunto al presente repositorio el cual nos dio mayor acierto 

Se realizo el archivo PRUEBA_CLASIFICADOR para comprobar el modelo se lo cargo y primero se uso imagenes con las que se entreno SOLO PARA VER QUE SE ESTE ASIGNANDO LAS CLASES DE MANERA CORRECTA Y TODO ESTE FUNCIONANDO BIEN y despues ya se probo con imagenes de validacion

Posteriormente se creo la Matriz de confusion para validar como quedo nuestro modelo donde pudimos evidenciar que nuestro modelo tenia una maxima presicion identificando gabetas vacias con una presicion del 100% y con una menor presicion de detecsion de la clase 8 


### Screenshot
![Entrenamiento del modelo]([/home/shadow2392/Pictures/Screenshots/1.png](https://github.com/geovanny2392/MODELO_CLASIFICADOR_CARNE/blob/main/1.png))
![Matriz de confusion]([/home/shadow2392/Pictures/Screenshots/2.png](https://github.com/geovanny2392/MODELO_CLASIFICADOR_CARNE/blob/main/2.png))

<span>![</span><span>Entrenamiento del modelo </span><span>]</span><span>(</span><span>[https://github.com/geovanny2392/MODELO_CLASIFICADOR_CARNE/blob/main/1.png</span><span>)</span>
<span>![</span><span>Matriz de confusion </span><span>]</span><span>(</span><span>https://github.com/geovanny2392/MODELO_CLASIFICADOR_CARNE/blob/main/2.png</span><span>)</span>




### Technologies
***
Se utilizo la siguiente tecnologia:
* [libreria keras]([https://example.com](https://keras.io/examples/vision/image_classification_from_scratch/)): Version 12.3 


