---
aliases: 
tags: []
---
Materia:: [[Matemáticas discretas]]
Relacionado:: 
# Definiciones
## Grafos
Es un conjunto, no vacío, de objetos llamados vértices (o nodos) y una selección de pares de vértices, llamados aristas (_edges_) en inglés que pueden ser orientados o no. Típicamente, un grafo se representa mediante una serie de puntos (los vértices) conectados por líneas (las aristas).
Los grafos son estructuras discretas que constan de vértices y aristas que conectan entre si esos vértices. Por lo tanto un grafo $G$ consta de dos partes: 
1. Un conjunto $V= V(G)$ cuyos elementos se denominan vértices, puntos o nodos de $G$.
2. Un conjunto $E = E(G)$ de pares de vértices distintos denominados aristas de $G$ .
- En teoría de grafos, sólo queda lo esencial del dibujo: la forma de las aristas no son relevantes, solo importa a qué vértices están unidas. La posición de los vértices tampoco importa, y se puede variar para obtener un dibujo más claro
- Es una pareja de conjuntos $G = (V,A)$, donde $V$ es el conjunto de vértices y $A$ es el conjunto de aristas, este último es un conjunto de pares de la forma $(u,v)$ tal que $u,v \in V$. Para simplificar, notaremos la arista $(a,b)$ como $ab$.
- Muchas redes de uso cotidiano pueden ser modeladas con un grafo: una red de carreteras que conecta ciudades, una red eléctrica o la red de drenaje de una ciudad. 
## Vértices 
Los vértices constituyen uno de los dos elementos que forman un grafo. Como ocurre con el resto de las ramas de las matemáticas, a la Teoría de Grafos no le interesa saber qué son los vértices. Diferentes situaciones en las que pueden identificarse objetos y relaciones que satisfagan la definición de grafo pueden verse como grafos y así aplicar la Teoría de Grafos en ellos.
- Los vértices cuentan con grados, mismos que podrán ser positivos o negativos, y son definidos como la cantidad de aristas que llegan o salen de él; para el caso de grafos no orientados, el grado de un vértice es simplemente la cantidad de aristas incidentes a este vértice. Por ejemplo, el grado positivo (salidas) de $d$ es 3, mientras que el grado negativo (llegadas) de $d$ es $0$
    - A un vértice del que solo salen aristas se le denomina **fuente**, por el contrario, a aquellos en los que sólo entran aristas se les denomina **pozo** o **sumidero**
## Subgrafos 
Un subgrafo de un grafo $G$ es un grafo cuyos conjuntos de vértices y aristas son subconjuntos de los de $G$. Se dice que un grafo $G$ contiene a otro grafo $H$ si algún subgrafo de $G$ es $H$ o es isomorfo a $H$ (dependiendo de las necesidades de la situación).
## Isomorfismo
En la rama de las matemáticas se le conoce como isomorfismo a la:
> "Correspondencia biunívoca que se registra entre dos estructuras algebraicas, manteniendo las operaciones. De este modo, si hay isomorfismo, el estudio de una estructura puede reducirse al de la otra"

Dicho de otra manera, se registra un isomorfismo entre dos estructuras en definitiva, si a cada elemento de una le corresponde solamente un elemento de la otra y lo mismo ocurre con cada operación

- El isomorfismo matemático es un morfismo, o sea que se trata de una aplicación que no altera la estructura interna; más precisamente, es un homomorfismo, porque ambos objetos tienen la misma estructura algebraica

# Estructuras de datos en la representación de Grafos 
Existen diferentes formas de almacenar grafos en una computadora. La estructura de datos usada depende de las características del grafo y el algoritmo usado para manipularlo. Entre las estructuras más sencillas y usadas se encuentran las listas y las matrices, aunque frecuentemente se usa una combinación de ambas. Las listas son preferidas en grafos dispersos porque tienen un eficiente uso de la memoria. Por otro lado, las matrices proveen acceso rápido, pero pueden consumir grandes cantidades de memoria. 
## Estructura de lista
1. Lista de incidencia: Las aristas son representadas con un vector de pares (ordenados, si el grafo es dirigido), donde cada par representa una de las aristas.
2. Lista de adyacencia: Cada vértice tiene una lista de vértices los cuales son adyacentes a él. Esto causa redundancia en un grafo no dirigido (ya que $A$ existe en la lista de adyacencia de $B$ y viceversa), pero las búsquedas son más rápidas, el costo de almacenamiento extra.
     En esta estructura de datos  la idea es asociar a cada vértice $i$ del grafo una lista que contenga todos aquellos vértices $j$ que sean adyacentes a él. De está forma sólo reservará memoria para los arcos adyacentes a $i$ y no para todos los posibles arcos que pudieran tener como origen $i$. El grafo por lo tanto, se representa por medio de un vector de $n$ componentes $(\rightarrow |V| = n)$ donde cada componente va a ser una lista de adyacencia correspondiente a cada uno de los vértices del grafo. Cada elemento de la lista consta de un campo indicando el vértice adyacente. En caso de que el grafo sea etiquetado, habrá que añadir un segundo campo para mostrar el valor de la etiqueta.
## Estructura matricial 
- Matriz de incidencia: El grafo está representado por una matriz de $A$ (aristas) por $V$ (vértices), donde $[arista-vertice]$ contiene la información de la arista $[1 - conectado, 0 - no conectado]$
- Matriz de adyacencia: El grafo está representado por una matriz cuadrada $M$ de tamaño $n^2$, donde $n$ es el número de vértices. Si hay una arista entre un vértice $x$ y un vértice $y$, entonces el elemento $m_{x,y}$ es $1$, de lo contrario, es $0$.
# Aristas dirigidas y no dirigidas 
En algunos casos es necesario asignar un sentido a las aristas, por ejemplo, si se requiere representar la red de las calles de una ciudad con sus direcciones únicas. El conjunto de aristas ahora será un subconjunto de todos los posibles pares ordenados de vértices, Con $(a,b) \neq (b,a)$. Los grafos que contienen aristas dirigidas se denominan **grafos orientados** o **grafos dirigidos**
## Grafos con aristas dirigidos 
Son aquellos en donde los vértices son conjuntos finitos no vacíos, la relación binaria es $E \subseteq V \times V$. El par ordenado $(V,E)$ es un grafo dirigido sobre $V$, o dígrafo, donde $V$ es el conjunto de vértices o nodos y $E$ es su conjunto de aristas. Escribimos $G= (V,E)$, para denotar tal dígrafo
## Grafos con aristas no dirigidos 
Cuando no importa la dirección de las aristas, la estructura $G= (V,E)$, donde $E$ es ahora un conjunto de pares no ordenados sobre $V$, es decir el conjunto de aristas representa una relación simétrica binaria, 	donde si $V_j$ y $V_k$ son vértices cualesquiera del conjunto de vértices $V$ de un grafo, $(V_j,V_k) \in E \rightarrow (V_j,V_k) \in E$. Decimos que tenemos un grafo no dirigido.
- Las aristas no orientadas se consideran bidireccionales para efectos prácticos (equivale a decir que existen dos aristas orientadas entre los nodos, cada una en un sentido).  
# Ciclos y caminos Hamiltonianos
Ciclo: Sucesión de aristas adyacentes, donde no se recorre dos veces la misma arista, y donde se regresa al punto inicial 
Ciclo Hamiltoniano: Parte de la definición de ciclo, con todas sus características, añadiendo además que el ciclo tiene que recorrer todos los vértices exactamente una vez (excepto el vértice del que parte y al cual llega). 
# Tipificación de Grafos de acuerdo a sus características 
- Grafos simples: Un grafo es simple si a lo más existe una arista uniendo dos vértices cualesquiera. Esto es equivalente a decir que una arista cualquiera es la única que une dos vértices específicos. Un grafo que no es simple se denomina multígrafo.
- Grafos conexos Un grafo es conexo si cada par de vértices está conectado por un camino; es decir, si para cualquier par de vértices $(a, b)$, existe al menos un camino posible desde a hacia $b$.
	- Un grafo es conexo si cada par de vértices está conectado por al menos dos caminos disjuntos; es decir, es conexo y no existe un vértice tal que al sacarlo el grafo resultante sea disco nexo.
	- En términos matemáticos la propiedad de un grafo de ser (fuertemente) conexo permite establecer con base en él una relación de equivalencia para sus vértices, la cual lleva a una partición de éstos en "componentes (fuertemente) conexas", es decir, porciones del grafo, que son (fuertemente) conexas cuando se consideran como grafos aislados. Esta propiedad es importante para muchas demostraciones en teoría de grafos.
- Grafos completos: Un grafo es completo si existen aristas uniendo todos los pares posibles de vértices. Es decir, todo par de vértices $(a, b)$ debe tener una arista $e$ que los une. 
  El conjunto de los grafos completos es denominado usualmente $K$ , siendo $K_n$ el grafo completo de $n$ vértices. 
  Un $K_n$, es decir, grafo completo de $n$ vértices tiene exactamente $\frac{n(n-1)}{2}$ aristas. 
  La representación gráfica de los $K_n$ como los vértices de un polígono regular da cuenta de su peculiar estructura.
- Grafos Bipartitos: Un grafo $G$ es bipartito si puede expresarse como $G = {V_1 \cup V_2, A}$ (es decir, sus vértices son la unión de dos grupos de vértices), bajo las siguientes condiciones: 
	- $V_1$ y  $V_2$ son disjuntos y no vacíos. 
	- Cada arista de A une un vértice de V1 con uno de V2 . 
	- No existen aristas uniendo dos elementos de V1 ; análogamente para V2 . 
	- Bajo estas condiciones, el grafo se considera bipartito, y puede describirse informalmente como el grafo que une o relaciona dos conjuntos de elementos diferentes, como aquellos resultantes de los ejercicios y puzzles en los que debe unirse un elemento de la columna A con un elemento de la columna B.
- 