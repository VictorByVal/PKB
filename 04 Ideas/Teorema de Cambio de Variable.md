---
aliases: 
tags:
---
Materia:: [[Estadística Inferencial]]
Subtema:: 
Relacionado:: 

# Procedimiento
1. Definir la variable aleatoria original: Sea $X$ una variable aleatoria con una función de densidad de probabilidad (FDP) $f_X(x)$.
2. Definir la transformación: Supongamos que queremos definir una nueva variable aleatoria $Y$ en términos de $X$, es decir:
   $$Y=g(X)$$
   donde $g(x)$ es una función inyectiva (uno a uno) en el dominio de interés.
3. Encontrar la función inversa: Si $g(x)$ es una función monótona, entonces existe una función inversa
   $$X = g^{-1}(Y)$$
4. Calcular la derivada de la función inversa:
   $$\frac{d}{dy} g^{-1}(y)$$
5. Calcular la nueva función de densidad $f_Y(y)$ se obtiene mediante la transformación:
   $$f_Y(y) = f_X(g^{-1}(y)) \left| \frac{d}{dy} g^{-1}(y) \right|$$
   donde:

- $f_X(x)$ es la función de densidad de $X$.
- $g^{-1}(y)$ es la función inversa de $g(x)$.
- $\left| \frac{d}{dy} g^{-1}(y) \right|$​​ es el valor absoluto del jacobiano, que ajusta los cambios en la escala de la variable.

# Glosario (Conceptos y definiciones)

# Notas Adicionales
- Se aplica en el ejercicio de [[Método de Máxima Verosimilitud]], cuando a la hora de calcular la esperanza, no nos quede $\mathbb{E}\left[x_i\right]$, sino que nos quede cualquier otra transformación. 
# Tasks

# Cuestionario

# Referencias 
