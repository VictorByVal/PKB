> [!concepto]
> 

> [!etimologia]
> 

>[!temas]+ 
>```dataview
>list 
>where contains(materia, [[Ciencia de Datos]])
>```

>[!diario]- Notas diarias
>```list
>from "Notas diarias"
>where contains(relacionado, [[Ciencia de Datos]])
>```

>[!done]+ Tareas
>```tasks
>not done 
>description includes [[Ciencia de Datos]]


- La estadística clásica se centra en la inferencia, un conjunto de procesos complejos para generar conclusiones acerca de largas poblaciones basado en pequeñas muestras. 
 
# Antecedentes 
- [John W. Tukey](https://es.wikipedia.org/wiki/John_W._Tukey) es considerado el padre de la ciencia de datos, debido a que tras la publicación de su libro "The Future of Data Analysis" se propuso una nueva disciplina que incluyera la inferencia estadística solo como un componente 
	- Con esto Tukey forjó un lazo entre las ciencias computacionales y la estadística e ingenierías 
	- Sus premisas originales siguen siendo aún sorpesivamente durables y forman parte de los fundamentos de la ciencia de datos 
	- En su libro "Exploratory Data Analysis", Tukey presentó simples gráficas (Boxplots, Scatterplots) que junto con un resumen estadístico (media, mediana, cuantiles, etc) ayudaba a hacerse una idea del conjunto de datos. 
- El creciente desarrollo computacional de la época ha propiciado un crecimiento de la cantidad de datos que se manejan y ha dado acceso a más grandes y un mayor número de datos
- Uno de los retos de la ciencia de datos es transformar el gran volumen de datos brutos en información accionable. 
# Tipos de datos estructurados (Taxonomía)
- Numéricos: Datos que son expresados en una escala numérica. 
	- Continuos: Involucran mediciones
	- Discretos: Involucran conteos
- Categóricos: Aquellos que solamente toman elementos de un conjunto definido de valores. 
	- Binarios: Aquellos que solo contienen dos categorías de valores ($1$ y $2$ o True y False)
	- Ordinales: Datos categóricos que tienen un orden específico
		- Ej. el caso de la base de datos del Titanic, que califica a los pasajeros de acuerdo a su nivel de tripulación $(1,2,3,4,5)$

> [!attention]
> Conocer esta información es importante debido a que dependiendo los tipos de datos con los que contemos será la manera en la que el software como R o Python usará estos datos para mejorar el rendimiento computacional, encima es importante para determinar el tipo de visualización, análisis de datos o modelo estadístico 

# Datos Rectangulares 
Es el término acuñado para matrices bidimensionales (tablas), con filas indicando casos o registros y columnas indicando variables 
- En python (pandas) y R el término acuñado para referirse a los datos rectangulares es *DataFrames*. 

# Datos No Rectangulares 
Son aquellos datos que no consisten de matrices bidimensionales (tablas) y que tienden a ser más complejos en cuanto a su estructura. 
- Ejemplo de esto son los datos producidos por el IoT, que tienden a ser series de tiempo y a representar coordenadas

