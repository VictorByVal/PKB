---
aliases: 
tags:
---
Materia:: [[Estadística Inferencial]]
Subtema:: 
Relacionado:: 


# Glosario (Conceptos y definiciones introductorias)
> [!concepto] 
>
- Error tipo I : Es cuando se rechaza la hipótesis nula, siendo esta verdadera. 
	- También se le suele llamar un falso negativo. 
	- Se le denota como $\alpha$ 
	- $P(\text{Rechazar } H_0 | H_0 \text{ Es verdadera})$
- Error tipo II : Es cuando no se rechaza la hipótesis nula, siendo esta errónea. 
	- También se le denomina como un falso positivo. 
	- Se le denota como $\beta$ 
	- $P(\text{No rechazar } H_0 | H_1 \text{ Es verdadera})$
	- A su complemento se le denomina como *Potencia de prueba* y es igual a $1-\beta$

# Elementos de una Prueba de Hipótesis 
1. Hipótesis Nula, $H_0$: Es una idea que tenemos respecto a una población (Conjetura inicial)
2. Hipótesis Alternativa, $H_a$: Conjetura alterna (Investigación)
	- La idea contra la cuál vamos a comparar nuestra hipótesis nula. 
	- Es la hipótesis a ser aceptada en caso de que $H_0$ sea rechazada
3. Estadístico de Prueba: Es una medición de las mediciones muestrales en las que la decisión estadística estará basada 
4. Región de Rechazo: Específica los valores del estadístico de prueba para el cuál la hipótesis nula ha de ser rechazada a favor de la hipótesis alternativa. 
	- En algunas notaciones es denotada como $RR$, en otras como $\xi*$ 
	- También se le denomina como región crítica 

Hipotesis: Es una idea que tenemos respecto a una población 

Hipótesis nula: $H_0$: Conjetura inicial
- Se va a comparar contra la Hipótesis alterna 

Hipótesis alterna $H_1$: Conjetura alterna (complemento)
- "Contra la cual vamos a comparar"

# Simple vs Simple 

$H_0 : \theta = \theta_0$ vs $H_1 : \theta = \theta_1$ 

$\Theta = \{\theta_0, \theta_1\}$

# Simple vs Compuesta 

$H_0 : \theta = \theta_0$ vs $H_1 : \theta \neq \theta_0$ 

$\Theta = \mathbb{R} = \{0,\infty\}$

# Otro esqueleto de Hipótesis 
- Hipótesis Simple $H_0 : \theta = 0.1, \theta = 0.9 \therefore \theta = \theta_0$
	- Se destaca porque se va a tener una igualdad  
	- Donde teta es el parámetro poblacional y teta 0 es la cantidad propuesta
- Hipótesis Compuesta $H_0 : \theta \leq 0.1$ o $\theta < 0.1$ o $\theta \geq 0.1$ o $\theta > 0.1$

En general el espacio parametral $\Theta$ se divide en dos regiones $\Theta_0$ y es respecto a la hipótesis nula. La segunda región va a ser $\Theta_1$ 

$$ \Theta = \Theta_0 \cup \Theta_1$$

Por lo tanto: 
- $H_0 : \theta \in \Theta_0$ vs $H_1 : \theta \in \Theta_1$

Es posible que nos estemos equivocando al tomar o al construir nuestras regiones. Lo que haremos es tomar la decisión de tal forma que la probabilidad de equivocarnos es pequeña.

# Procedimiento 
1. Construir el estadístico de prueba
2. Construir la región crítica $\xi^* = \{x | \text{Rechaza } H_0\}$
 
# Notas Adicionales
- En general si $\alpha$ es pequeña en una prueba de hipótesis, entonces $\beta$ suele ser grande o viceversa. Por lo tanto se opta por dejar fija una $\alpha$ y se intenta buscar una región de rechazo que minimice $\beta$ o equivalente maximice $1-\beta$ (Potencia de prueba). 
# Tasks

# Cuestionario

# Referencias 
