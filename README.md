# AWS-ImagePredictionAnalyzer

![diagram](https://github.com/ccalvop/AWS-ImagePredictionAnalyzer/assets/126183973/067f1659-b6b5-4e08-b919-73ea186113d3)

**Objetivo:**

Desplegar un modelo pre-entrenado ResNet-18 para realizar predicciones de imágenes.

**Servicios de AWS involucrados:**

  - AWS Lambda
  - Amazon S3
  - Amazon API Gateway

**Archivos y código a crear:**

  - Modelo pre-entrenado ResNet-18 almacenado en Amazon S3.
  - Sitio web estático alojado en Amazon S3 para cargar y mostrar imágenes.
  - Función de AWS Lambda para procesar las imágenes y generar predicciones basadas en probabilidades utilizando el modelo ResNet-18.
  - Amazon API Gateway para permitir que el sitio web llame a la función de Lambda.
  - Configuración de archivos como "config.js" para establecer parámetros y URL de predicción.

**Resultado esperado:**

Un sistema funcional que permite cargar imágenes en un sitio web estático y realizar predicciones utilizando el modelo pre-entrenado ResNet-18 a través de AWS Lambda. Las predicciones se mostrarán en el sitio web, y se evaluará el rendimiento y la precisión de las predicciones obtenidas.


**Modelo ResNet-18:** ![LINK](https://arxiv.org/abs/1512.03385)

En este proyecto, se carga el modelo pre-entrenado ResNet-18 desde un archivo almacenado en Amazon S3. El código Python utilizado en la función de AWS Lambda carga la arquitectura del modelo y los pesos pre-entrenados, permitiendo realizar predicciones de imágenes basadas en probabilidades. Este modelo ha sido entrenado en un gran conjunto de datos y es capaz de reconocer una amplia variedad de objetos e imágenes.

```
El modelo ResNet-18 es una arquitectura de red neuronal convolucional (CNN) profunda que se utiliza en tareas de clasificación de imágenes. Está basada en el paper "Deep Residual Learning for Image Recognition" (Aprendizaje Residual Profundo para el Reconocimiento de Imágenes) y fue propuesta por Kaiming He, Xiangyu Zhang, Shaoqing Ren y Jian Sun. 

ResNet-18 se caracteriza por su capacidad para entrenar redes neuronales más profundas y superar el problema del desvanecimiento del gradiente. Utiliza conexiones residuales que permiten que las capas aprendan las diferencias entre la entrada y la salida deseada, facilitando así el entrenamiento de redes más profundas. Además, la arquitectura ResNet-18 consta de capas de convolución, capas de agrupamiento y capas completamente conectadas.
```

***

![underconstruction_ccalvop](https://user-images.githubusercontent.com/126183973/234038103-2ab74b58-e1ed-48b3-b45d-74de0e3f18cf.jpg)
