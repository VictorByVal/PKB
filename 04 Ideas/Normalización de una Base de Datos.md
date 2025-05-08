---
aliases: 
tags:
---
Materia:: [[Bases de Datos]]
Subtema:: [[Reglas de la Normalización de una Base de Datos]]
Relacionado:: 

>[!concepto] Normalización 
>Proceso mediante el cuál se organizan los datos en una base de datos relacional para reducir la redundancia  y mejorar la integridad de los datos. Este proceso se logra dividiendo una tabla grande en tablas más pequeñas y definiendo relaciones entre ellas mediante claves foráneas. 

# Objetivos
1. **Eliminar redundancias**: Evita la duplicación de datos para reducir el espacio de almacenamiento y mejorar la consistencia 
2. **Mejorar la integridad de los datos**: Minimiza la posibilidad de inconsistencias y errores en los datos. 
3. **Facilitar el mantenimiento**: Permite realizar actualizaciones, inserciones y eliminaciones  sin afectar la integridad de la información. 
4. **Optimizar consultas**: Reduce la complejidad y el tiempo de ejecución de ciertas consultas en la base de datos. 

# Formas normales
La normalización se realiza en diferentes niveles llamados formas normales (FN), cada una con reglas específicas: 
1. Primera Forma normal (1FN): 
	- Se eliminan los valores repetidos en una misma celda (valores atómicos). 
	- Cada columna debe contener un solo valor (no listas ni conjuntos). 
2. Segunda Forma normal (2FN): 
	-  Debe cumplir con la 1FN
	-  Se eliminan las dependencias parciales (cada columna no clave debe depender completamente de la llave primaria). 
3. Tercera Forma normal  (3FN):
	-  Debe cumplir con la 2FN 
	-  Se eliminan las dependencias transitivas (una columna no clave no debe depender de otra columna no clave). 
4. Forma normal o de Boyce-Codd (3FN): 
	-  Es una mejora de la 3FN
	-  Se eliminan las dependencias funcionales que no están completamente determinadas por la clave primaria. 
5. Cuarta y quinta forma normal (4FN y 5FN)
	-  Se eliminan las dependencias multivaluadas y anomalías más complejas en las bases de datos muy avanzadas. 

# Glosario (Conceptos y definiciones)

# Notas Adicionales
- Un ejemplo sería un escultor, que va primero generando el esquema general de la escultura, para posteriormente ir esculpiendo y perfeccionando la silueta de su pieza de arte. 
- En algunos casos se puede optar por desnormalizar para mejorar el rendimiento en consultas frecuentes. 
# Tasks

# Cuestionario

# Referencias 
