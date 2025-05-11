---
aliases: 
tags:
---
Materia:: [[Estadística Inferencial]]
Subtema:: 
Relacionado:: 

# Elementos de una Prueba de Hipótesis 
1. Hipótesis Nula, $H_0$: Es una idea que tenemos respecto a una población (Conjetura inicial)
2. Hipótesis Alternativa, $H_a$: Conjetura alterna.
	- La idea contra la cuál vamos a comparar nuestra hipótesis nula. 
3. Estadístico de Prueba:
4. Región de Rechazo:

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

1. Construir la región crítica $\xi^* = \{x | \text{Rechaza } H_0\}$ 

# Glosario (Conceptos y definiciones)
- Región Crítica: Región en donde se va a rechazar $H_0$ 
- Error tipo 1: Es cuando se rechaza la hipótesis nula, siendo esta verdadera. 
	- También se le suele llamar un falso negativo. 
- Error tipo 2: Es cuando no se rechaza la hipótesis nula, siendo esta errónea. 
	- También se le denomina como un falso positivo. 
# Notas Adicionales
- A la probabilidad del error tipo 1 se le denota como $\alpha$ 
	- $P(\text{Rechazar } H_0 | H_0 \text{ Es verdadera})$
- A la probabilidad del error tipo 2 se le denota como $\beta$ 
	- $P(\text{No rechazar } H_0 | H_1 \text{ Es verdadera})$
	- Al complemento del error tipo 2 se le denomina como Potencia de prueba $1-\beta$ 
- En general si $\alpha$ es pequeña en una prueba de hipótesis, entonces $\beta$ suele ser grande o viceversa. Por lo tanto se opta por dejar fija una $\alpha$ y se intenta buscar una región de rechazo que minimice $\beta$ o equivalente maximice $1-\beta$ (Potencia de prueba). 
# Tasks

# Cuestionario

# Referencias 
