Materia:: [[Algebra Lineal]]

# Suma de matrices 
- Se obtiene sumando elemento por elemento 
- Para sumar dos matrices, estas deben tener las mismas dimensiones (La misma cantidad de filas y columnas)
# Resta de matrices 
- Se obtiene restando elemento por elemento 
- Para restar dos matrices, estas deben tener las mismas dimensiones (La misma cantidad de filas y columnas)
# Multiplicación por un escalar
Implica multiplicar cada elemento de la matriz por dicho escalar
# Producto Escalar 
Es una operación que toma dos vectores y produce un escalar (número real o complejo), su fórmula es $u\cdot v = u_1 \cdot  v_1 + u_2 \cdot v_2 + \dots + u_n  \cdot v_n$

# Producto de matrices 
- Se obtiene de multiplicar las filas de la primera matriz por las columnas de la segunda y sumando los productos resultantes 
- Para que la multiplicación sea posible, el número de columnas de la primera matriz debe ser igual al número de filas de la segunda 
$$ A^{[2\times3]} \text{ y } B^{[3\times3]}$$
# Inversión de matrices 
Es una operación que nos permite encontrar una matriz inversa para una matriz dada. La matriz inversa de una matriz $A$ se denota como $A^{-1}$ y tiene la propiedad de que cuando se multiplica por $A$, el resultado es la matriz de identidad
**Nota**: No todas las matrices tienen una inversa. Para que una matriz tenga una inversa, debe ser una matriz cuadrada y su determinante debe ser distinto de cero. 
- Se puede encontrar su inversa utilizando el Método de Gauss-Jordan
# Método de Gauss-Jordan 
Es una técnica utilizada para resolver sistemas de ecuaciones lineales y encontrar la solución a un sistema de ecuaciones, determinar si una matriz es invertible y encontrar la inversa de una matriz 
- Es una variable del método de eliminación de Gauss y lleva el proceso un paso adicional para convertir una matriz en su forma identidad (Escalonada, reducida por filas), lo que facilita la determinación de soluciones y propiedades de la matriz