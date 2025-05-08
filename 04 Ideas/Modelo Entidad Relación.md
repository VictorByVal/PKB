---
alias: 
- MER
---
Materia:: [[Bases de Datos]]
Parent:: [[Modelos de Datos]]
>[!concepto]
>Es una herramienta conceptual utilizada en el diseño de bases de datos para representar y estructurar los datos de manera visual y comprensible. 
# Componentes del Modelo Entidad Relación
- *Entidades:* Representan objetos o conceptos del mundo real que tienen una existencia independiente en la base de datos, como una persona, un lugar, un objeto físico o un evento. 
	- Cada entidad se describe mediante un conjunto de atributos que detallan sus características
	- Para ellos es que se recopilan, almacenan y mantienen datos
	- Cada entidad solamente puede tener una llave foránea. 
	- **Tipos de Entidades**
		- *Tangibles:* Son todos aquellos objetos físicos que podemos ver, tocar o sentir. 
		- *Intangibles:* Todos aquellos eventos u objetos conceptuales que no podemos ver, aun sabiendo que existen, por ejemplo: la entidad materia, sabemos que existe, sin embargo, no la podemos visualizar o tocar. 
- *Relaciones:* Describen como las entidades están conectadas entre si. Por ejemplo, una relación podría describir que un estudiante se inscribe en un curso, o que un cliente realiza un pedido. 
- *Atributos:* Son las propiedades o características de las entidades y las relaciones. Por ejemplo, una entidad "Estudiante" podría tener atributos como "Nombre", "Edad" y "Matricula". 
	- Son características de entidades
- Llaves primarias: Atributos únicos para una entidad y que no se repiten. 
- Llaves foráneas: Atributo que relaciona una entidad con otra. 
	- Es la llave primaria de otra tabla. 

![[Diagrama de un Modelo Entidad-Relación]]

# Cuestionario 
> [!question] Describa la diferencia entre una llave primaria y una llave foránea en un MER.
>> [!success]- Answer
>> Una llave primaria es un atributo único que identifica una entidad, mientras que una llave foránea es un atributo que relaciona una entidad con otra, actuando como la llave primaria de otra entidad.

> [!question] Complete la frase: En un MER, los `____` describen las características de las `____`.
>> [!success]- Answer
>> atributos, entidades

> [!question] ¿Qué representa una entidad en un modelo entidad-relación?
> a) Un programa de software
> b) Un objeto o concepto del mundo real
> c) Un algoritmo de búsqueda
> d) Una relación entre tablas
>> [!success]- Answer
>> b) Un objeto o concepto del mundo real

> [!question] Analice la afirmación: 'Cada entidad solamente puede tener una llave foránea'. ¿Es completamente cierta o hay excepciones posibles? Justifique su respuesta con ejemplos.
>> [!success]- Answer
>> La afirmación 'Cada entidad solamente puede tener una llave foránea' no es completamente cierta. Una entidad puede tener múltiples llaves foráneas si necesita relacionarse con varias otras entidades. Por ejemplo, una entidad 'Producto' podría tener una llave foránea que relaciona con una entidad 'Categoría' y otra llave foránea que relaciona con una entidad 'Proveedor'. Esto permite representar relaciones múltiples entre entidades en un modelo de datos.

> [!question] ¿Cuál de los siguientes NO es un componente fundamental de un modelo entidad-relación?
> a) Atributos
> b) Relaciones
> c) Consultas SQL
> d) Entidades
>> [!success]- Answer
>> c) Consultas SQL

> [!question] Mencione al menos tres ejemplos concretos de entidades y sus atributos, usando ejemplos que no estén en el texto.
>> [!success]- Answer
>> Ejemplos de entidades y sus atributos pueden incluir:\n\n*   **Entidad:** Producto \n    **Atributos:** Nombre, precio, descripción, ID de categoría\n*   **Entidad:** Cliente\n    **Atributos:** Nombre, dirección, correo electrónico, número de teléfono\n*   **Entidad:** Pedido\n    **Atributos:** Número de pedido, fecha, estado, ID de cliente

> [!question] Complete la frase: Una `____` es un atributo único que identifica de forma inequívoca a una `____`.
>> [!success]- Answer
>> clave primaria, entidad

> [!question] ¿Cuáles son los dos tipos de entidades mencionados en el texto?
> a) Complejas y Simples
> b) Relacionales y No relacionales
> c) Tangibles e Intangibles
> d) Internas y Externas
>> [!success]- Answer
>> c) Tangibles e Intangibles

> [!question] Explique la importancia de las relaciones en un modelo entidad-relación.
>> [!success]- Answer
>> Las relaciones en un MER muestran cómo las entidades están conectadas entre sí, representando las interacciones y dependencias entre los diferentes objetos o conceptos del mundo real. Esto permite representar de manera precisa las estructuras de datos y las relaciones entre ellos.

> [!question] Un modelo entidad-relación (MER) es una herramienta exclusivamente digital para el diseño de bases de datos.
>> [!success]- Answer
>> False

> [!question] Las entidades en un MER siempre representan objetos físicos tangibles.
>> [!success]- Answer
>> False