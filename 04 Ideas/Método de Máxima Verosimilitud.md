---
aliases: 
- MLE
- Maximum Likelihood Estimation
tags:
---
Materia:: [[Estadística Inferencial]]
Relacionado:: 

>[!concepto]
>Es un procedimiento estadístico para estimar los parámetros de un modelo de probabilidad a partir de datos observados. La idea central es encontrar los valores de los parámetros que maximizan la función de verosimilitud, es decir, aquellos que hacen que los datos observables sean más probables bajo el modelo asumido. 

# Expresión Matemática 
Dado un conjunto de datos $x = \{x_1,x_2,\dots,x_n\}$ y un modelo de distribución de probabilidad $f(x|\theta)$ con parámetros $\theta$, la función de verosimilitud se define como: 
$$ l(\theta) = P(x|\theta) = \prod_{i=1}^{n}f(x_i|\theta)$$
# Procedimiento 
1. Definir la función de verosimilitud
   Se debe expresar como el producto de las funciones de densidad o masa de probabilidad evaluadas en los datos observados. 
2. Tomar el logaritmo natural (log-verosimilitud) 
   Para simplificar los cálculos y convertir productos en sumas 
   $$ L (\theta) = \ln L(\theta) = \sum_{i=1}^{n}\ln f(x_i|\theta)$$
3. Derivar respecto a $\theta$ y encontrar el máximo 
   Se calcula la derivada $\frac{d}{d\theta}l(\theta)$ y se iguala a cero para encontrar los valores críticos. 
4. Verificar que es un máximo
   Se usa la segunda derivada $\frac{d^2}{d\theta^2}l(\theta)$ para asegurarse de que el punto encontrado corresponde a un máximo. 

# Glosario

# Notas 
- La $l$ en la notación del método de máxima verosimilitud proviene de *likelihood* o "verosimilitud". 
- En este método $\theta$ es el valor que se quiere encontrar, es el parámetro desconocido, por lo tanto en cada función de probabilidad se debe derivar aquellos parámetros que se deseen conocer, o que se desconozcan. 
- Hay una diferencia entre la $l$ y la $L$ y es que la $L$ mayúscula en términos de notación se emplea para referirse al logaritmo natural o  "logaritmo" de $l$ siendo conocida también como "log-verosimilitud"
# Tasks

# Referencias 
