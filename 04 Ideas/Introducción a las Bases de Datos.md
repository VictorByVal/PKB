---
Periodo: Parcial
aliases: 
tags:
---
Materia:: [[Bases de Datos]]
Relacionado:: 
# Definiciones de Base de datos
> "Colección de datos lógicamente relacionados" - Elmásri Navathe 

> "Sistema computacional que permite que un conjunto de datos pueda ser mantenido y que esté disponible cuando se requiera, se conoce como el sistema de Base de Datos" 

- Esta definición introduce un sistema computacional, aunque si menciona su disponibilidad al ser requerida. 

> "Colección de archivos relacionados con la finalidad de permitir el manejo de la información para su procesamiento"

- Esta definición no introduce ningún software ni sistema computacional, a diferencia de la segunda. 
# Componentes elementales 
- Información 
- Equipo 
- Programas 
- Usuarios 
# Razones para utilizar un sistema de base de datos 
- Ofrece a la organización un control centralizado de su información. 
- Contrasta con el enfoque donde cada aplicación tiene sus propios datos (archivos), de modo que los datos están dispersos y difíciles de controlar.
# Ventajas del Enfoque de Base de Datos 
- Disminución de redundancias de datos 
- Evitar inconsistencias de datos 
- Compartir datos 
- Mantener la integridad 
- Definición y aplicación de restricciones de seguridad 
- Independencia de datos. 
#### Independencia de datos 
>"Inmunidad de las aplicaciones ante cambios en la estructura de almacenamiento y en la técnica de acceso a los datos" (C.J. Date)

Es decir, las aplicaciones no dependen de la estructura o técnica de acceso de los datos. 
- Triada CID 
#### Ventajas de las BD vs Archivos Convencionales 
- Independencia de datos - programas 
- Eliminación de información redundante 
- Integridad de los datos
- Eliminación de información incongruente
- Globalización de la información (Ente general) 
- Compartición de información
#### Arquitectura de tres niveles
- El objeto de la arquitectura de tres niveles es la separación entre las aplicaciones de usuario y la base de datos. 
- Los tres esquemas (que corresponden a los tres niveles) son sólo una forma de descripción de los datos los únicos datos que existen están en el nivel físico. 
- Aunque algunos SGBD (Sistemas de Gestión de Base de Datos) se basan en la arquitectura de tres niveles no es fácil distinguir en ellos estos tres niveles. 
- Los tres niveles son: Físico, Conceptual y Lógico
	- El nivel lógico son los programas donde se gestionaran la base de datos.
	- Físico es simplemente el Hardware.
	- Conceptual es los diagramas y la manera en la que la base de datos es estructurada.