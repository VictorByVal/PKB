---
aliases: 
tags:
---
Materia::[[Introducción a la Programación]]
Relacionado:: [[Compilación vs Interpretación]], [[Que hace el interprete]]

Por supuesto, dicha composición tiene que ser correcta en muchos sentidos:

- **alfabéticamente** – un programa debe estar escrito en un alfabeto reconocible, como romano, cirílico, etc.
- **léxicamente** – cada lenguaje de programación tiene su diccionario y hay que dominarlo; afortunadamente, es mucho más simple y pequeño que el diccionario de cualquier idioma natural;
- **sintácticamente** – cada idioma tiene sus reglas y hay que obedecerlas;
- **semánticamente** – el programa tiene que tener sentido.

Desafortunadamente, un programador también puede cometer errores con cada uno de los cuatro sentidos anteriores. Cada uno de ellos puede hacer que el programa se vuelva completamente inútil.

Supongamos que has escrito con éxito un programa. ¿Cómo persuadimos a la computadora para que lo ejecute? Tienes que convertir tu programa en lenguaje de máquina. Afortunadamente, la traducción la puede hacer una computadora, lo que hace que todo el proceso sea rápido y eficiente.

Hay dos formas diferentes de **transformar un programa de un lenguaje de programación de alto nivel a un lenguaje de máquina**:
- Compilación: El programa fuente se traduce una vez (sin embargo, este acto debe repetirse cada vez que se modifique el código fuente) al obtener un archivo (por ejemplo, un .exe si el código esta destinado a ejecutarse en MS Windows) que contiene el código máquina. Ahora se puede distribuir el archivo en todo el mundo; el programa que realiza esta traducción se llama compilador o traductor.
- Interpretación: Tú o cualquier usuario del código puede traducir el programa fuente cada vez que se debe ejecutar. El programa que realiza este tipo de transformación se denomina interprete, ya que interpreta el código cada vez que se pretende ejecutar. También significa que no puedes simplemente distribuir el código fuente tal cual, porque el usuario final también necesita el intérprete para ejecutarlo

Debido a algunas razones muy fundamentales, un lenguaje de programación de alto nivel en particular está diseñado para caer en una de estas dos categorías.

Hay muy pocos lenguajes que puedan compilarse e interpretarse. Por lo general, un lenguaje de programación se proyecta con este factor en la mente de sus constructores - ¿será compilado o interpretado?

¿Qué significa todo esto para ti?

- Python es un **lenguaje interpretado**. Esto significa que hereda todas las ventajas y desventajas descritas. Por supuesto, agrega algunas de sus características únicas a ambos conjuntos.
- Si deseas programar en Python, necesitarás el **intérprete de Python**. No podrás ejecutar tu código sin él. Afortunadamente, **Python es gratuito**. Esta es una de sus ventajas más importantes.

# Glosario
- **Lenguajes de Scripting**: Lenguajes diseñados para ser utilizados en la interpretación 
- **Scripts**: Programas codificados con Lenguajes de Scripting. 
- **Programación Informática**: Acto de componer los elementos del lenguaje de programación seleccionado en el orden que provocará el efecto deseado. 

# Notas 

# Tasks

# Referencias 
