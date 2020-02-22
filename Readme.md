# Práctica NLP Searching - BootCamp Big Data & Machine Learning

Este es el repositorio que contiene los archivos necesarios para realizar la práctica de la asignatura de NLP Searching del Bootcamp Big Data y Machine Learning IV cursado en KeepCoding en 2019-2020.

## Objetivo

La práctica esta dividida en 4 o 5 subapartados, que ya tenéis en este mismo Notebook. Estos subapartados estan aquí para que rellenéis el código que hace falta para la realización de la práctica. Obviamente podéis usar tantas celdas como os hagan falta, es más es de agradecer si el código final esta algo "limpio". Usar funciones, algo de comentario, etc, etc...

Usaremos 2 datasets, uno para el primer ejercicio, y otro para el resto de ejercicios.

Ejercicios:

1.   Machine Learning vs Deep Learning (Acordaros que hay que implementar el pipeline visto en clase entero)
    1.1. Implementación de un modelo de Sentiment Analysis con algún algoritmo de Machine Learning Clásico.
    1.2. Implementación de un modelo de Sentiment Analysis con alguna arquitectura de Deep Learning.
    1.3. Breve Comparación de resultados. Confusion Matrix.
    
2. Hacer Analysis de los tweets del segundo dataset. Que temas aparecen? Como se representan estos temas? De que hablan unos y otros?

3. Escoged a uno de los dos presidentes, y escribid tweets como ellos, usando un Modelo Generativo.

En cada ejercicio, espero explicaciones y razonamientos del porque una arquitectura y no otra, por ejemplo en Deep Learning, porque usar Convolutionals en lugar de recurrentes, o en Machine Learning, Bayes en lugar de SVM. Hay que explicar el pipeline, sobretodo el preproceso de datos, con lo que habrá que hacer un pequeño estudio de que datos tenemos, y si hay cosas que se pueden ignorar, si hacéis stemming, o no, etc, etc...

## Dataset 

Los datasets no están incluidos en el repositorio para no ocupar espacio. Se pide que se haga un pequeño estudio de los datos que tenemos, también habrá que hacer algún tratamiento de los mismos y puede que haya datos que no sean relevantes. Todo lo relacionado con el análisis básico y tratamiento de los datos está en los siguientes Notebooks.

Análisis exploratorio y tratamiento de datos dataset 1:
[Dataset Ejercicio 1](00_1_AnalisisDataset1.ipynb)

Análisis exploratorio y tratamiento de datos dataset 2:
[Dataset Ejercicio 2 y 3](00_2_AnalisisDataset2.ipynb)

## Resolución del problema

La resolución de la práctica se ha hecho en Python usando varios notebooks de Jupyter donde en cada uno se explica todo el procedimiento paso a paso.

### 1. Machine Learning vs Deep Learning
Implementar modelo de deep learning y otro de machine learning. Comparar resultados y hacer matriz de confusión.
#### 1.1. Implementación de un modelo de Sentiment Analysis con algún algoritmo de Machine Learning Clásico.
[Machine Learning Clásico](01_1_ML_Clasico.ipynb)
#### 1.2. Implementación de un modelo de Sentiment Analysis con alguna arquitectura de Deep Learning.
[Deep Learning](01_2_DeepLearning.ipynb)

### 2. Análisis tweets segundo dataset
Hacer Analysis de los tweets del segundo dataset. Analizar los temas que se mencionan, cómo se representan y de qué se habla en los tweets.

### 3. Escoger presidente y escribir tweets como él 
Escoger uno de los dos presidentes y hacer un modelo generativo que escriba tweets como él.