Materia:: [[Algebra Lineal]]
1. Obtener las ecuaciones, junto con sus restricciones y la función objetivo
2. Convertir las inecuaciones en ecuaciones con holguras e igualar la función objetivo a cero (Incluyendo a la función objetivo)
3. Diseñar la primer tabla simplex: 

| Variables básicas | z   | X1  | X2  | X3  | X4  | X5  | R   |     |
| ----------------- | --- | --- | --- | --- | --- | --- | --- | --- |
| X3                |     |     |     |     |     |     |     |     |
| X4                |     |     |     |     |     |     |     |     |
| X5                |     |     |     |     |     |     |     |     |
| Z                 |     |     |     |     |     |     |     |     |

Donde: 
- $X3$ hasta $X5$ serán variables de holgura 
- $Z$ es la ==función objetivo== 
- $R$ Son los resultados de las inecuaciones (Los que están a la derecha del igual)
5. Encontrar la ==columna pivote== (tomando en la fila $Z$ el mayor valor negativo)
6. Dividir los resultados (La columna $R$) entre la columna pivote 
7. Se toma el menor valor de los Resultados (Columna $R$) siendo esa la fila pivote
8. La intersección entre la Fila pivote y la columna pivote será el ==Elemento pivote== 
9. Se sustituye a la Variable que ocupa la fila pivote (==Variable saliente==) por la que esté establecida en la columna pivote (==Variable entrante==)
10. Se divide la fila pivote entre el elemento pivote siendo esta la ==Fila Nueva== para dicha variable y siendo la ==Fila Clave== 
11. Para obtener la Fila Nueva de las demás variables y la fila $Z$ (La función objetivo) se emplea la siguiente fórmula: 

$$ FV - FC \cdot CP$$
Donde: 
- $FV$ Es la fila vieja de la variable (La que se desea renovar)
- $FC$ Es la fila clave 
- $CP$ Es el coeficiente pivote 

12. Se repite el proceso a partir del paso 5, iterando las veces que sean necesarias hasta que los valores en $Z$ resulten positivos, dando así por finalizado el proceso. *texto en cursiva*