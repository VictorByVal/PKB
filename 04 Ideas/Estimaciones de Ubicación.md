---
aliases:
  - Medidas de tendencia central
tags:
---
Materia::
Subtema:: 
Relacionado:: 

> [!concepto]
> 

# Media 
- También conocida como valor promedio 
- En inglés es conocida como *mean* o *average value*
- Es la suma de todos los valores, dividido entre el número de valores
- Se representa como $\bar{x}$ (pronunciado como x barra) 
$$\text{Media} = \bar{x} = \frac{\sum_{i=1}^{n}x_i}{n}$$

# Media recortada 
- Es aquella que se calcula al exceptuar para el cálculo a un numero definido de valores ordenados a cada uno de los extremos para posteriormente tomar la media de los valores restantes. 
$$\text{Media recortada} = \bar{x} = \frac{\sum_{i=p+1}^{n-p}x_i}{n-2p}$$
- Donde $p$ es la cantidad de valores que se desea remover de cada extremo. 
- Tiene la particularidad de que elimina la influencia de los valores extremos. 
- En inglés se le conoce como *Trimmed Mean*

# Media ponderada 
- En inglés se le conoce como *Weighted mean*
- Se calcula al multiplicar cada dato por un determinado peso o ponderación y dividiendo su suma por la suma de los pesos. 
$$ \text{Media ponderada} = \text{Weighted mean} = \bar{x}_w = \frac{\sum_{i=1}^{n}w_ix_i}{\sum_{i=1}^{n}w_i}$$
- Se emplea para aquellos casos donde: 
	- Algunos valores son intrinsecamente más variables que otros, en estos casos a esos valores se les asigna pesos o ponderaciones menores (Debido a que son menos fiables). 
	- Los datos que recolectamos no representan de forma equitativa los diferentes grupos que estamos interesados en medir. 
		- En aquellos casos se le da un mayor peso a los grupos que fueron representados de manera escasa. 


# Mediana 
Es el número de en medio en una lista ordenada de los datos
- En inglés se le conoce como *median*
- Para aquellos casos donde se tiene un número par de datos, la mediana no es realmente un valor que se encuentre dentro del conjunto de datos, sino que se toman los dos valores del medio y se les saca una media

Variables with measured or count data might have thousands of distinct values. A basic step in exploring your data is getting a “typical value” for each feature (variable): an estimate of where most of the data is located (i.e., its central tendency). 

- [ ] Continuar con esta nota [[Ciencia de Datos]] #task 
