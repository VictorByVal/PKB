---
aliases: 
tags:
---
Materia:: [[Introducción a la Programación]]
Relacionado:: [[Compilación vs Interpretación]]

Supongamos una vez más que has escrito un programa. Ahora, existe como un **archivo de computadora**: un programa de computadora es en realidad un fragmento de texto, por lo que el código fuente generalmente se coloca en **archivos de texto**.

Nota: tiene que ser **texto puro**, sin decoraciones como diferentes fuentes, colores, imágenes incrustadas u otros medios. Ahora debes invocar al intérprete y dejar que lea tu archivo fuente.

El intérprete lee el código fuente de la forma habitual en la cultura occidental: de arriba a abajo y de izquierda a derecha. Hay algunas excepciones: se cubrirán más adelante en el curso.

En primer lugar, el intérprete verifica si todas las líneas posteriores son correctas (utilizando los cuatro aspectos cubiertos anteriormente).

Si el compilador encuentra un error, finaliza el trabajo inmediatamente. El único resultado en este caso es un **mensaje de error**.

El intérprete te informará dónde se encuentra el error y qué lo causó. Sin embargo, estos mensajes pueden ser engañosos, ya que el intérprete no puede seguir tus intenciones exactas y puede detectar errores a cierta distancia de sus causas reales.

Por ejemplo, si intentas utilizar una entidad de un nombre desconocido, causará un error, pero el error se descubrirá en el lugar donde intenta usar la entidad, no donde se introdujo el nombre de la nueva entidad.

En otras palabras, el motivo suele estar ubicado un poco antes en el código, por ejemplo, en el lugar donde tenías que informar al intérprete que ibas a utilizar la entidad del nombre.

Si la línea se ve bien, el intérprete intenta ejecutarlo (nota: cada línea generalmente se ejecuta por separado, por lo que el trío "leer-verificar-ejecutar" se puede repetir muchas veces, más veces mas que el número real de líneas en el archivo fuente, ya que algunas partes del código puede ejecutarse más de una vez).

También es posible que una parte significativa del código pueda ejecutarse con éxito antes de que el interprete encuentra un error. Este es un comportamiento normal en este modelo de ejecución.

Puedes preguntarte ahora: ¿cuál es mejor? ¿El modelo de "compilación" o el modelo de "interpretación"? No hay una respuesta obvia. De haberlo existido, uno de estos modelos habría dejado de existir hace mucho tiempo. Ambos tienen sus ventajas y sus desventajas.
# Glosario

# Notas 

# Tasks

# Referencias 
