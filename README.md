# Evidencia 1
[Archivo ejecutable (.py) en repositorio](https://github.com/solishiguera/M2-E1/blob/main/evidencia1.py)
## Modelo
Durante esta práctica, se desarrollará un modelo de **regresión lineal de primer orden**, con el objetivo de predecir la cantidad de calorías que contiene una bebida de starbucks a partir de la cantidad de carbohidratos que contiene.

## Dataset
Para esta evidencia, utilizaré el data set de los valores nutricionales de las bebidas de Starbucks. [Starbucks dataset Kaggle](https://www.kaggle.com/datasets/starbucks/starbucks-menu)

## Variables

#### Variable dependiente (Y) : Calorías
#### Variable independiente (X) : Carbohidratos

#### División de datos
Utilizaremos el **70%** de nuestros datos para entrenamiento (63 filas) y **30%** para validación (27 filas)

### Definición de parámetros
Se define una *tasa de aprendizaje* (alpha) de **0.00001** para nuestra *Gradiente Descendente*.

### Iteraciones del modelo
Iniciamos corriendo nuestro modelo **1,000 iteraciones**, y este encontrará los valores de $\theta_0$ y $\theta_1$ que mejor se ajusten a los datos.

### Función de costo
Se calcula la función de costo para nuestros dos datasets: El dataset de entrenamiento y el de validación. Con este podemos determinar la manera en la que se ajusta nuestro modelo. 
<br> En este caso:
* Función de costo para data set de validación =  1555.58
* Función de costo para data set de entrenamiento: 971.14


### Función de hipótesis
* $\theta_0$ = 2.38
* $\theta_1$ = 6.22

### Graficando resultados
#### Variables
  * Variable dependiente (Y) : Calorías
  * Variable independiente (X) : Carbohidratos
#### En este apartado, graficamos nuestro modelo obtenido. 
* Como podemos observar, se calcula el valor estimado para nuestros dos datasets y se grafican.
* Vemos como nuestro dataset de validación está de color naranja, y los valores que se predicen son de color azul.
* Por otro lado, nuestro dataset de entrenamiento se muestra de color amarillo, mientras que los valores que se predicen son de color verde.
* Por último, observamos una línea roja punteada que representa nuestro modelo de regresión lineal de 1er orden. 

<img width="1121" alt="Screen Shot 2022-09-14 at 9 06 44 PM" src="https://user-images.githubusercontent.com/69832749/190296321-c8ff8d03-5399-4aff-9d35-e13f19be3812.png">

#### Diego Solis Higuera
#### A00827847
#### 14 de septiembre de 2022

[Google Colab](https://colab.research.google.com/drive/1J8lcFmTJAOaGyQr-5SqXKq5a3pjI9L_B)

