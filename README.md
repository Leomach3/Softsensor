# Introducción.

*Aqui encontraras un modelo de softsensor en el dataset ‘Kamyr digester’ para el proceso de fabricacion de pulpa y papel.
*Tambien una breve descripcion de lo que son los softsensor y el metodo empleado en su desarrollo que fue PLS (Partial Least Squares)

## Softsensor.

Un softsentor es un término ampliamente utilizado para describir sensores basados ​​en software, que es una técnica para estimar parámetros relacionados con la calidad "difíciles de medir" en procesos industriales. También se conocen como sensores virtuales, estimadores/modelos inferenciales y sensores basados ​​en observadores. Los softsensors se basan en modelos matemáticos o empíricos que asignan un conjunto de variables de proceso de entrada a un parámetro de calidad, de modo que los parámetros de calidad "difíciles de medir" en las industrias de proceso se puedan estimar con precisión utilizando un conjunto de variables de proceso de entrada "fáciles de medir".

Yasith S. Perera, D.A.A.C. Ratnaweera, Chamila H. Dasanayaka, Chamil Abeykoon,The role of artificial intelligence-driven soft sensors in advanced sustainable process industries: A critical review,Engineering Applications of Artificial Intelligence,Volume 121,2023,105988,ISSN 0952-1976,https://doi.org/10.1016/j.engappai.2023.105988.(https://www.sciencedirect.com/science/article/pii/S0952197623001720)

## PLS (Partial Least Squares)

El método Partial Least Squares (PLS) es una técnica de análisis estadístico y de regresión utilizada para modelar relaciones entre variables independientes (predictoras) y variables dependientes (respuestas), especialmente cuando hay muchas variables predictoras y estas están altamente correlacionadas. A continuación, te explico el método de manera sencilla:

# Partial Least Squares (PLS) - Una Visión General

## Introducción

Partial Least Squares (PLS) es un método estadístico poderoso utilizado principalmente para el modelado predictivo y el análisis de relaciones entre dos matrices de variables. Es particularmente útil en situaciones donde hay muchos predictores y la multicolinealidad es una preocupación. PLS puede manejar datos donde el número de predictores supera el número de observaciones y se utiliza ampliamente en campos como la quimiometría, la bioinformática y las ciencias sociales.

## Cómo Funciona PLS

Aquí hay una explicación sencilla de cómo funciona:

1. **Descomposición de Datos**: PLS descompone los predictores (X) y las respuestas (Y) en un conjunto de componentes ortogonales (variables latentes). Estos componentes son combinaciones lineales de las variables originales.

2. **Maximización de la Covarianza**: El método encuentra componentes que maximizan la covarianza entre X y Y. Esto significa que identifica patrones en los predictores que son más relevantes para predecir las variables de respuesta.

3. **Regresión en Variables Latentes**: Una vez identificados los componentes, PLS realiza regresión en estas variables latentes para predecir las respuestas.

## Conceptos Clave

- **Variables Latentes**: Son los factores subyacentes extraídos de los datos originales. Capturan la información más importante necesaria para predecir las respuestas.

- **Covarianza**: PLS se enfoca en maximizar la covarianza entre los predictores y las respuestas. La covarianza es una medida de cuánto cambian juntos dos variables.

## Ventajas de PLS

- **Manejo de Multicolinealidad**: PLS puede manejar datos altamente colineales, lo que lo hace adecuado para conjuntos de datos con muchos predictores interrelacionados.

- **Reducción de Dimensionalidad**: Al reducir los datos a unas pocas variables latentes, PLS simplifica el modelo manteniendo la información esencial.

- **Poder Predictivo**: PLS está diseñado para maximizar el poder predictivo del modelo, haciéndolo muy efectivo para tareas de regresión.



