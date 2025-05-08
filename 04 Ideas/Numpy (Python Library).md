Materia:: [[Python]]
Tipo:: Librería

La convención comúnmente empleada de alias para Numpy es `np`, donde en código usualmente a la hora de importar la librería se emplea el código a continuación: `import numpy as np`, donde la biblioteca podrá ser referida posteriormente como un objeto.

Para generar un arreglo n dimensional, se tendrá que crear un objeto, para posteriormente llamar al objeto correspondiente a la librería emplear la función `array()`, donde dentro del paréntesis se tendrá que anexar una lista o lista de listas, que serán las filas, y las columnas serán la cantidad de elementos que exista dentro de cada una de las listas.  
```python 
ar1 = np.array([0,1,2,3]) #Generación de un arreglo unidimensional 
ar2 = np.array([[0,3,5], [2,8,7]]) # Generación de un arreglo multidimensional (dos dimensiones)
```
para conocer más acerca de la cantidad de filas y columnas de una matriz de Numpy se puede ejecutar el método `shape` del objeto que hayamos creado para definir la matriz, en el caso de arriba podría ser:
```python 
ar1.shape
```
