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


Para calcular la moda, se depende directamente de los datos y la frecuencia con la que cada uno aparece.

Empleando la tabla ordenada de la mediana podemos contar con mayor facilidad y por ende determinamos que:

**Modas obtenidas**
  
  | X1| X2| X3|
  |---|---|---|
  | 1  | 3  | 17  |

Tener en mente:

En este caso las tres variables X1,X2 y X3 presentan un tipo de moda llamado **"unimodal"** en la cuál solo un valor presenta la mayor cantidad de apariciones.  

Para calcular la desviación estandar, se debe primero encontrar el valor de la varianza empleando la siguiente formula en el caso de una población:


$$
\sigma^2 = {\frac{\sum_{i=1}^{n}(x_i - \bar{x})^2}{n}}
$$

Donde:
- xᵢ: Son los valores individuales del conjunto de datos.

- x̄: Media de los datos.

- n: Es el número de elementos en el conjunto.


**NOTA:** para el desarrollo de este punto no se usará la formula de varianza cuando hay una muestra puesto que poseemos la población como tal.

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

