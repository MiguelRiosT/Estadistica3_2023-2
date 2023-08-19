# Punto 1 - Tarea 1 - Estadistica3_2023-2
## Solucion:

1.Teniendo en cuenta los siguientes datos:

|X1|X2|X3|
|--|--|--|
| 4 | 4 | 28 |
| 2 | 3 | 24 |
| 2 | 4 | 30 |
| 3 | 5 | 32 |
| 1 | 3 | 18 |
| 3 | 6 | 41 |
| 3 | 6 | 44 |
| 0 | 1 | 5 |
| 1 | 3 | 18 |
| 0 | 0 | 1 |
| 5 | 9 | 62 |
| 1 | 2 | 17 |
| 2 | 3 | 24 |
| 1 | 3 | 19 |
| 3 | 6 | 42 |
| 4 | 8 | 56 |
| 4 | 8 | 56 |
| 3 | 6 | 44 |
| 5 | 9 | 64 |
| 1 | 2 | 17 |
| 1 | 2 | 17 |

1.1 ¿Cuál es la media, mediana y desviación estándar?, y la moda y los
valores repeticiones de la moda para los datos categóricos.

[**Solucion**]

## MEDIA

Para calcular la media, se debe hacer uso de la siguiente formula:


$$
\bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i
$$

Donde:
- x̄: Representa la media (promedio).
- n: Es el número de elementos en el conjunto.
- xᵢ: Son los valores individuales del conjunto.

Por lo tanto, se procede a calcular la media de X1,X2 y X3 con n=21 

X1 = (4+2+2+3+1+3+3+0+1+0+5+1+2+1+3+4+4+3+5+1+1) = 49

X2 = (4+3+4+5+3+6+6+1+3+0+9+2+3+3+6+8+8+6+9+2+2) = 93

X3 = (28+24+30+32+18+41+44+5+18+1+62+17+24+19+42+56+56+44+64+17+17) = 659

x̄1 = 49/21 = 2.333

x̄2 = 93/21 = 4.428

x̄3 = 659/21 = 31.380


**Medias obtenidas**
  
  | X̄1| X̄2| X̄3|
  |---|---|---|
  | 2.333  | 4.428  | 31.380  |

<br>

## MEDIANA

Para calcular la mediana, se deben tener ciertas consideraciones:

- Se debe ordenar el conjunto de números de menor a mayor

- Si el conjunto de números es par 

$$
  \text{Mediana} = \frac{1}{2} \cdot (x_{\frac{n}{2}} + x_{\frac{n}{2}+1})
$$


- Si el conjunto de números es impar

$$
 \text{Mediana}= \frac{n+1}{2} 
$$

Se procede a ordenar los números de menor a mayor

|X1|X2|X3|
|--|--|--|
| 0 | 0 | 1 |
| 0 | 1 | 5 |
| 1 | 2 | 17 |
| 1 | 2 | 17 |
| 1 | 2 | 17 |
| 1 | 3 | 18 |
| 1 | 3 | 18 |
| 1 | 3 | 19 |
| 2 | 3 | 24 |
| 2 | 3 | 24 |
| **2** |**4** | **28** |
| 3 | 4 | 30 |
| 3 | 5 | 32 |
| 3 | 6 | 41 |
| 3 | 6 | 42 |
| 3 | 6 | 44 |
| 4 | 6 | 44 |
| 4 | 8 | 56 |
| 4 | 8 | 56 |
| 5 | 9 | 62 |
| 5 | 9 | 64 |

Con los datos ya ordenados de menor a mayor, tenemos un n=21 

por lo tanto, aplicaremos 


$$
 \frac{n+1}{2} 
$$

(21+1)/2=11, de los datos ordenados la mediana será la que se encuentré en la posición 11

**Medianas obtenidas**
  
  | X1| X2| X3|
  |---|---|---|
  | 2  | 4  | 28  |

<br>

## MODA

Para calcular la moda, se depende directamente de los datos y la frecuencia con la que cada uno aparece.

Empleando la tabla ordenada de la mediana podemos contar con mayor facilidad y por ende determinamos que:

**Modas obtenidas**
  
  | X1| X2| X3|
  |---|---|---|
  | 1  | 3  | 17  |

Tener en mente:

En este caso las tres variables X1,X2 y X3 presentan un tipo de moda llamado **"unimodal"** en la cuál solo un valor presenta la mayor cantidad de apariciones.  


<br>

## DESVIACIÓN ESTÁNDAR

Para calcular la desviación estandar, se debe primero encontrar el valor de la varianza empleando la siguiente formula en el caso de una población:


$$
\sigma^2 = {\frac{\sum_{i=1}^{n}(x_i - \bar{x})^2}{n}}
$$

Donde:
- xᵢ: Son los valores individuales del conjunto de datos.

- x̄: Media de los datos.

- n: Es el número de elementos en el conjunto.


**NOTA:** 

Cuando se calcula la desviación estándar estamos midiendo la dispersión o variabilidad de un conjunto de datos con respecto a su promedio.

para el desarrollo de este punto no se usará la formula de varianza cuando hay una muestra puesto que poseemos la población como tal.

Primero partamos del valor de la media que ya se habia encontrado junto con el valor n:

X̄1= 2.333, n=21

luego, calculemos la varianza

$$
\sigma^2=\frac{(4-2.333)^2 + (2-2.333)^2 + (2+1.333)^2+(3-2.333)^2 + (1-2.333)^2 + (3+1.333)^2+(3-2.333)^2 + (0-2.333)^2 + (1+1.333)^2+(0-2.333)^2 + (5-2.333)^2 + (1+1.333)^2+(2-2.333)^2 + (1-2.333)^2 + (3+1.333)^2+(4-2.333)^2 + (4-2.333)^2 + (3+1.333)^2+(5-2.333)^2 + (1-2.333)^2 + (1+1.333)^2}{21}
$$

$$
\sigma^2 = 2.222
$$

teniendo la varianza, la desviación estándar es la raíz cuadrada de la varianza por lo tanto la desviación estándar para X1 es

$$
\sigma = 1.490
$$


Para X2: usando X̄2= 4.428, n=21

$$
\sigma^2=\frac{(4-4.428)^2 + (3-4.428)^2 + (4+4.428)^2+ ... +(9-4.428)^2 + (2-4.428)^2 + (2+4.428)^2}{21}
$$

$$
\sigma^2 = 6.530
$$


$$
\sigma = 2.555
$$




Para X3: usando X̄3=31.380, n=21

$$
\sigma^2=\frac{(28-31.380)^2 + (24-31.380)^2 + (30+31.380)^2+ ... +(64-31.380)^2 + (17-31.380)^2 + (17+31.380)^2}{21}
$$

$$
\sigma^2 = 314.807
$$


$$
\sigma = 17.742
$$

**Desviaciones estándar obtenidas**
  
  | X1| X2| X3|
  |---|---|---|
  | 1.490  | 2.555  | 17.742  |

<br>
<br>

1.1 **Resultados obtenidos**

**Medias obtenidas**
  
  | X̄1| X̄2| X̄3|
  |---|---|---|
  | 2.333  | 4.428  | 31.380  |

**Medianas obtenidas**
  
  | X1| X2| X3|
  |---|---|---|
  | 2  | 4  | 28  |

**Modas obtenidas**
  
  | X1| X2| X3|
  |---|---|---|
  | 1  | 3  | 17  |

**Desviaciones estándar obtenidas**
  
  | X1| X2| X3|
  |---|---|---|
  | 1.490  | 2.555  | 17.742  |


<br>
<br>
<br>
<br>


1.2 Dibujar un Boxplot a mano:

Para dibujar un boxplot es necesario tener en mente los siguientes aspectos:

- Ordenar los datos de menor a mayor.

- Valor mínimo: es el valor más pequeño del conjunto de datos.

- Valor máximo: es el valor más alto del conjunto de datos.

- Q1: Es el valor que divide los datos en el 25% inferior. El 25% de los datos están por debajo de este valor.

- Q2: equivalente a la mediana

- Q3: Es el valor que divide los datos en el 25% superior. El 75% de los datos están por debajo de este valor.

- IQR(Interquartile Range) - RI(Rango intercuatilico): Es el resultado de Q3-Q1

El IQR mide el rango en el que se encuentra el 50% central de los datos, es una medida útil para entender cómo se distribuyen los datos alrededor de la mediana y cómo se alejan de los valores extremos.

Limites: Nos ayudan a identificar con más precisión aquellos valores que son atípicos.


- Límite Inferior del Bigote = Q1 - 1.5 * IQR. 

- Límite Superior del Bigote = Q3 + 1.5 * IQR.

NOTA: si un conjunto de datos no posee algun valor que supere los limites anteriormente mencionados los bigotes del BoxPlot solo se mostrarán hasta los valores minimos y máximos de los datos.

<br>



Se adjuntan calculos para X1:

![CalculosBoxPlotX1](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/CalculosBoxPlotX1.jpg)

**Gráfico Boxplot para X1**

![BoxPlotX1](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/BoxPlotX1.jpg)


<br>

Se adjuntan calculos para X2:

![CalculosBoxPlotX2](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/CalculosBoxPlotX2.jpg)

**Gráfico Boxplot para X2**

![BoxPlotX2](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/BoxPlotX2.jpg)

<br>

Se adjuntan calculos para X3:

![CalculosBoxPlotX3](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/CalculosBoxPlotX3.jpg)

**Gráfico Boxplot para X3**

![BoxPlotX3](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/BoxPlotX3.jpg)

<br>
<br>
<br>
<br>

1.3 Calcular covarianza entre las dos variables X1 y X2

Se emplea la siguiente formula de la covarianza:

![Formula covarianza](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/FormulaCov.png)

En dónde n será el número de datos en el conjunto 

Se adjuntan los calculos realizados:


![CalculosCovarianza](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/CalculosCovarianza.png)

**Cov(X1,X2) = 3.571**

1.4 ¿Cuál es la correlación entre X1 y X2?

Se emplea la siguiente fórmula de correlación:

![Formula correlacion1](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/Formula1Correlacion.png)

Se adjuntan los calculos realizados:

![CalculosCorrelacion1](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/Calculos1Correlacion.png)

**Cor(X1,X2) = 0.9375**

Se valida el calculo de la correlación empleando la siguiente formula:

![Formula correlacion2](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/Formula2Correlacion.png)

Se adjuntan los calculos realizados con la segunda formula:

![CalculosCorrelacion2](https://github.com/MiguelRiosT/Estadistica3_2023-2/blob/main/Tarea1/doc/ImagenesEmpleadas/Calculos2Correlacion.png)

También se obtiene:
**Cor(X1,X2) = 0.9375**

Tener en mente lo siguiente:

- Cor = 0, variables independientes.

- Cor= +1, > 0.4 (y depende de la variable x), explica cambios positivos

- Cor= +1, <-0.4 (y depende de la variable x), explica cambios negativos

<br>

**Observación**

Se puede observar que la variable X1 explica la variabilidad de X2 y que es una relación positiva

es decir, cuando X1 cambia genera un cambio positivo en X2.


<br>
<br>

1.5 Explicar la relación entre covarianza y correlación


Partamos primero por entender ambas por separado:

- **covarianza** es una medida numérica que mide como 2 variables varían de
forma conjunta.

La covarianza mide cómo dos variables varían juntas, en términos de si tienden a aumentar o disminuir juntas

- **correlación** permite investigar las relación lineal entre dos variables.

La correlación mide la relación lineal entre dos variables, considerando tanto la dirección como la fuerza de la relación.

En base a esto, se puede decir que la relación entre covarianza y correlación se centra en que la correlación se calcula a partir de la covarianza, pero se considera más preciso el valor arrojado por la correlación.


1.6 Usando la tabla de datos, calcule el resultado del algoritmo K-means con 3 grupos, es decir 3 clusters.

**Dudas sobre cómo se realiza con k=3**



