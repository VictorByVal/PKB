---
aliases: 
tags:
---
Materia:: [[Bases de Datos]]
Subtema:: 
Relacionado:: 

# Primera Forma normal 
>[!caution] Nota
>Una relación se encuentra en primera forma normal si las tablas contienen un solo valor por cada celda. 

- Todos los ingresos en cualquier columna (atributo) deben ser del mismo tipo. 
- Cada columna debe tener un nombre único: el orden de las columnas en la tabla no es importante. 
- Dos filas o renglones de una misma tabla no deben ser identicas, aunque el orden de las filas no es importante. 
- Por lo general, la mayoría de las relaciones cumplen con estas características, así podemos decir que la mayoría de las relaciones se encuentran en la primera forma normal. 
# Segunda Forma Normal 
>[!caution] Nota
>Una relación se encuentra en segunda forma normal si todos sus atributos que no son claves (llaves) dependen por completo de la clave y cumple con las reglas de la primera forma normal. 

# Tercera Forma Normal (3FN)
>[!caution] Nota
>Una relación se encuentra en tercera forma normal si no existen dependencias transitivas[^1] entre los atributos y está en segunda forma normal. 



# Glosario (Conceptos y definiciones)
[^1]: Dependencias Transitivas: En una afinidad (tabla bidimensional) que tiene por lo menos 3 atributos (A,B,C) hay dependencia transitiva si: 


- 
- El atributo A determina a B. 
- B determina a C 
- Pero C no determina a A. 
# Notas Adicionales

# Tasks

# Cuestionario

# Referencias 
