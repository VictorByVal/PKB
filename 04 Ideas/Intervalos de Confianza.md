---
aliases:
  - Estimadores de Intervalo
tags:
---
Materia:: [[Estadística Inferencial]]
Subtema:: 
Relacionado:: [[Estandarización]]

> [!concepto]
> Es una regla que específica el método para usar las mediciones muestrales en el cálculo de dos números que forman los puntos extremos del intervalo. 

Bajo un caso ideal un intervalo de confianza tiene dos propiedades: 
1. Contiene el parámetro objetivo $\theta$
2. Su amplitud será relativamente pequeña (Uno o ambos puntos extremos del intervalo, siendo funciones de las mediciones muestrales)

# Fórmula 

$$P(\hat{\theta}_L \leq \theta \leq \hat{\theta}_U) = 1 - \alpha$$

Donde: 
- $\hat{\theta}_L:$ Es el límite de confianza inferior. 
- $\hat{\theta}_U:$ Es el limite de confianza superior. 
- $1 - \alpha:$ Es el coeficiente de confianza. 
- $\theta:$ Es el parámetro objetivo. 

## Consideraciones adicionales 
- Al intervalo de confianza $\left[\hat{\theta}_L, \hat{\theta}_U\right]$ se le denomina intervalo de confianza bilateral. 
- También es posible formar un intervalo de confianza unilateral tal que: 
$$P(\hat{\theta}_L \leq \theta) = 1-\alpha$$

# Componentes 
- Los puntos extremos superior e inferior de un intervalo de confianza se denominan límites de confianza superior e inferior, respectivamente. 
- Coeficiente de confianza: Es la probabilidad de que un intervalo de confianza (aleatorio) incluya a $\theta$ (una cantidad fija) 
	- Identifica la fracción de veces, en un muestreo repetido, que los intervalos construidos contienen al parámetro objetivo $\theta$. 

La probabilidad de que el estimador sea igual al parámetro poblacional es prácticamente de cero. 
- Por lo mismo a la hora de reportar un estimador también se suele dar un intervalo de confianza, alrededor del cuál se va a encontrar el verdadero parámetro poblacional. 

A la hora de obtener un intervalo de confianza se suelen tomar intervalos con una probabilidad del 95% hasta el 99%, no se toma el 100% debido a que la información que nos brinda es redundante, prácticamente nos dice unicamente el conjunto númerico al cuál pertenece el parámetro, y no nos brinda un rango fiable. 




# Glosario (Conceptos y definiciones)
- Cantidad Pivotal: Es una función de la muestra cuya fórmula depende del parámetro pero su distribución no depende del parámetro. 
	- Un ejemplo de una cantidad pivotal es la estandarización
# Notas Adicionales
- En el entorno laboral los intervalos de confianza me sirven para amarrarme el dedo y en dado caso de que mi pronóstico no sea acertado, se encuentre dentro de un margen, que me de un rango mayor de acción y de éxito. 
# Tasks

# Cuestionario

# Referencias 
