Materia:: [[Algebra Lineal]]
- Rectangular: Tiene diferentes números de filas y columnas
$$
\begin{vmatrix} 2 & 5 & 8 \\ 6 & 7 & 1 \end{vmatrix}
$$
- Fila: Una matriz rectangular, pero con una sola fila
$$
\begin{vmatrix} 2 & 5 & 8 \end{vmatrix}
$$
- Columna: Una matriz rectangular, pero con una sola columna
$$ \begin{vmatrix} 2 \\ 5 \\ 8 \end{vmatrix} $$
- Nula: Matriz cuyos elementos son iguales a cero
$$ \begin{vmatrix} 0 & 0 & 0 \\ 0 & 0 & 0 \\ 0&0&0 \end{vmatrix} $$
- Cuadrada de orden n: Matriz que tiene el mismo número de filas que de columnas.
$$ \begin{vmatrix} 2&4&8 \\ 8&9&10\\4&5&6\end{vmatrix}$$
- Diagonal: Es un tipo de matriz cuadrada en la que los elementos que no se encuentran en la diagonal principal son iguales a cero
	- La diagonal principal es la línea que va desde la esquina superior izquierda hasta la esquina inferior derecha de la matriz 
$$ \begin{vmatrix}2&0&0\\0&4&0\\0&0&8\end{vmatrix}$$
- Escalar: Es una matriz diagonal en la que todos los elementos presentes en la diagonal principal son iguales
$$\begin{vmatrix}2&0&0\\0&2&0\\0&0&2\end{vmatrix}$$
- Identidad: Se trata de una matriz escalar en la que los elementos de la diagonal principal son iguales a uno, mientras que el resto de los elementos son iguales a cero
$$\begin{vmatrix}1&0&0\\0&1&0\\0&0&1\end{vmatrix}$$
- Opuesta: Es aMquella que es opuesta a otra cuyos elementos tienen un signo contrario a la matriz principal
    - A la matriz opuesta a $A$ se le denomina $-A$ y todos los elementos del conjunto son contrarios a los elementos de la matriz $A$
$$A = \begin{vmatrix}-1&7&8\\4&3&2\\1&-2&9\end{vmatrix} \hspace{2cm} -A = \begin{vmatrix}1&-7&-8\\-4&-3&-2\\-1&2&-9\end{vmatrix}$$
- Transpuesta: Se trata de la matriz que se obtiene al convertir las filas en columnas
    - Se utiliza el superíndice $t$ para representarla y su dimensión es $n \times m$
$$A= \begin{vmatrix}1&2&3\\4&5&6\\7&8&9\end{vmatrix} \hspace{2cm} A^t = \begin{vmatrix}1&4&7\\2&5&8\\3&6&9\end{vmatrix}$$
- Triangular superior: Se trata de una matriz cuadrada en la que todos los elementos por debajo de la diagonal principal son cero
$$\begin{vmatrix}4&-2&3\\0&7&5\\0&0&1\end{vmatrix}$$
- Triangular inferior: Aquella en la que todos los elementos por encima de la diagonal principal son cero 
$$\begin{vmatrix}1&0&0\\4&3&0\\5&6&1\end{vmatrix}$$