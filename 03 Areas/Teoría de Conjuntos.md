Materia:: [[Probabilidad y estadística]], [[Matemáticas discretas]]

> [!concepto]
> Es una rama de las matemáticas que estudia las colecciones de objetos, llamados conjuntos, y sus relaciones entre si. Proporcionando un marco formal para definir, manipular y analizar estructuras matemáticas fundamentales. 

> [!etimologia]
> 

>[!temas]+ 
>```dataview
>list 
>where contains(materia, [[Teoría de Conjuntos]])
>```

>[!diario]- Notas diarias
>```list
>from "Notas diarias"
>where contains(relacionado, [[Teoría de Conjuntos]])
>```

>[!done]+ Tareas
>```tasks
>not done 
>description includes [[Teoría de Conjuntos]]


- Conjuntos: Es cualquier colección de objetos bien definida
	- Con "Bien definida" se refiere a que es fácil decidir si un objeto pertenece a la colección o no.
	- Casi todos los objetos matemáticos son conjuntos, pese a cualquier propiedad adicional que puedan poseer
	- Son completamente conocidos cuando todos sus miembros son conocidos
	- Se dice que dos conjuntos $A$ y $B$ son iguales si tienen los mismos elementos y se denota como $A=B$ 
- Elementos o miembros del conjunto: Son los objetos que integran un conjunto. 

# Espacio Muestral  
Espacio muestral (Conjunto Universal): Es el conjunto de todos los posibles resultados de un experimento aleatorio
- Es denotado como $S$ que a la hora de expresarse de forma explícita se haría como sigue: 
$$S = \{a_1, a_2, \dots , a_n \}$$
Donde dentro de los corchetes se tendrían que enlistar y delimitar por comas todos los posibles resultados del experimento aleatorio mismo que puede ser definido de forma explicita o ímplicita mediante el uso de un rango.
$$S =  \{0, \infty\}$$

## Clasificación de los espacios muestrales
- Contables (Discretos) : Son aquellos que pueden ser puestos en una regla de correspondencia $1:1$ con el subconjunto de los números enteros o que contiene un número finito de elementos. 
- Incontables: Son aquellos que se encuentran en todo el conjunto de los números reales $\mathbb{R}$ y que por lo tanto no se pueden 
# Eventos 
Es cualquier colección de posibles resultados de un experimento, es decir cualquier subconjunto de $S$, incluyendo $S$ en sí misma. 

# Notas adicionales
- Los *diagramas de Venn*: Son herramientas para representar de forma conveniente los conjuntos y las relaciones entre ellos