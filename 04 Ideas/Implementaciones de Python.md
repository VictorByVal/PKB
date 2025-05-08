Materia:: [[Python]]

Además de Python 2 y Python 3, hay más de una versión de cada uno.

Siguiendo la [Página wiki de Python](https://wiki.python.org/moin/PythonImplementations), una _implementación_ de Python se refiere a "un programa o entorno que brinda soporte para la ejecución de programas escritos en el lenguaje Python, representado por la Implementación de Referencia de CPython."

La implementación _tradicional_ de Python, llamada **CPython**, es la versión de referencia del lenguaje informático Python de Guido van Rossum, y se suele llamar simplemente "Python". Cuando escuches el nombre _CPython_, lo más probable es que se use para distinguirlo de otras implementaciones alternativas no tradicionales.

Pero, lo primero es lo primero. Están los Pythons que son mantenidos por la gente reunida alrededor de la PSF ([Python Software Foundation](https://www.python.org/psf-landing/)), una comunidad que tiene como objetivo desarrollar, mejorar, expandir y popularizar Python y su entorno. El presidente del PSF es el mismo Guido von Rossum, y por eso, estos pythons se llaman **canónicos**. También se consideran **Pythons de referencia**, ya que cualquier otra implementación del lenguaje debe seguir todos los estándares establecidos por la PSF.

Guido van Rossum usó el lenguaje de programación "C" para implementar la primera versión de su lenguaje y esta decisión aún está vigente. Todos los Pythons que provienen del PSF están escritos en el lenguaje "C". Hay muchas razones para este enfoque. Uno de ellos (probablemente el más importante) es que gracias a él, Python puede ser portado y migrado fácilmente a todas las plataformas con la capacidad de compilar y ejecutar programas en lenguaje "C" (prácticamente todas las plataformas tienen esta función, lo que abre muchas posibilidades de expansión). oportunidades para Python).

Esta es la razón por la cual la implementación de PSF a menudo se denomina **CPython**. Este es el Python más influyente entre todos los Pythons del mundo.

**Haz clic en las imágenes para obtener más información sobre los miembros de la familia Python y algunas de las implementaciones alternativas de Python más populares.**

# Cython 
Es una de las posibles soluciones al rasgo de Python más doloroso (La falta de eficiencia). Los cálculos matemáticos grandes y complejos pueden ser fácilmente codificados en Python (mucho más fácil que en "C" o en cualquier otro lenguaje tradicional), pero la ejecución del código resultante puede requerir mucho tiempo. 

¿Cómo se reconcilian estas dos contradicciones? Una solución es escribir tus ideas matemáticas usando Python, y cuando estés absolutamente seguro de que tu código es correcto y produce resultados válidos, puedes traducirlo a "C". Ciertamente, "C" se ejecutará mucho más rápido que Python puro. 

Esto es lo que pretende hacer Cython: Traducir automáticamente el código de Python (limpio y claro, pero no demasiado rápido) al código "C" (complicado y hablador, pero ágil).

# Jython
"J" es de Java. Imagina un Python escrito en Java en lugar de C. Esto es útil, por ejemplo, si desarrollas sistemas grandes y complejos escritos completamente en Java y deseas agregarle cierta flexibilidad de Python. El tradicional CPython puede ser difícil de integrar en un entorno de este tipo, ya que C y Java viven en mundos completamente diferentes y no comparten muchas ideas comunes. 

Jython puede comunicarse con la estructura Java existente de manera más efectiva, es por esto que algunos proyectos lo encuentran útil y necesario. 

Nota: La implementación actual de Jython sigue los estándares de Python 2. Hasta ahora, no hay Jython conforme Python 3

# PyPy
- Es un Python dentro de un Python
- Representa un entorno de Python escrito en un lenguaje similar a Python llamado RPython (Restricted Python), en realidad es un subconjunto de Python. 
- El código fuente de PyPy no se ejecuta de manera interpretativa, sino que se traduce al lenguaje de C y luego se ejecuta por separado. 
- Resulta útil si se desea probar cualquier característica nueva que pueda se o no introducida en la implementación de Python, es más fácil verificarla con PyPy que con CPython
	- Resulta útil para las personas que desarrollan Python
- Es compatible con Python 3
# MicroPython
- Implementación eficiente de software de código abierto de Python 3 que está optimizada para ejecutarse en microcontroladores, incluye un pequeño subconjunto de la biblioteca estándar de Python, pero está repleto de una gran cantidad de funciones, como mensajes interactivos o números enteros, de precisión arbitraria, así como módulos que dan acceso al programador a hardware de bajo nivel. 
- Creado originalmente por Damien George
	- Programador Australiano
	- En 2013 realizó una exitosa campaña en Kickstarter y lanzó la primera versión de MicroPython con una placa de desarrollo con tecnología STM32F4 llamada pyboard. 
	- En 2017, MicroPython se utilizó para crear CircuitPython, otro lenguaje de programación  de código abierto que se ejecuta en el hardware del microcontrolador, que es un derivado del lenguaje de MicroPython. 
