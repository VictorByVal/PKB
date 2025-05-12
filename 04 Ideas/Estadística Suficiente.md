---
aliases: 
tags:
---
Materia:: [[Estadística Inferencial]]
Subtema:: 
Relacionado:: 

> [!concepto]
> Función de los datos muestrales que contiene toda la información necesaria sobre un parámetro desconocido de la distribución de la población. 
 
 Formalmente, una estadística $T(X)$ es suficiente para un parámetro $\theta$ si la distribución condicional de los datos $X$, dado $T(X)$, no depende de $\theta$.

# Definición formal (Criterio de Factorización de Neyman)

Sea $X = (X_1, X_2, ..., X_n)$ una muestra aleatoria de una distribución con función de densidad o función de probabilidad $f(X | \theta)$. Una estadística $T(X)$ es suficiente para $\theta$ si existen funciones $g(T(X), \theta)$ y $h(X)$ tales que:

$$P(x | T(x),\theta) = P(x|T(x))$$ 

Donde: 
- $T(x)$ es la estadística suficiente. 

# Procedimiento 

Para determinar: 

1. Sustituir la fórmula de la probabilidad condicional con los valores de la distribución. 
2. Sustituir los valores de la fórmula de la probabilidad condicional con la función de distribución y remplazar a $x_i$ con $t$, $y$ o el parámetro que se nos indique de acuerdo a notación. 
3. Eliminar términos en el numerador y denominador con la finalidad de solamente dejar el parámetro remplazado. 

# Glosario (Conceptos y definiciones)

# Notas Adicionales
- Los estadísticos suficientes a menudo se pueden usar para desarrollar estimadores que tienen varianza mínima entre todos los estimadores insesgados. 
# Tasks

# Cuestionario

# Referencias 
