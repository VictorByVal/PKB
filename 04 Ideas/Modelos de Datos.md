---
aliases: 
tags:
---
Materia:: [[Bases de Datos]]
Relacionado:: 

>[!concepto]
>es una colección de herramientas conceptuales para describir los datos, las relaciones que existen entre ellos, semántica asociada a los datos y restricciones de consistencia. 
- Desempeñan un papel importante en el proceso de diseño de una base de datos al ofrecer facilidades de abstracción que ayudan a representar la realidad. 
Los sistemas de datos pueden clasificarse de acuerdo a las estructuras de datos y a los operadores presentados al usuario

- Entre los sistemas más antiguos se encuentran los modelos de red y jerárquicos (pre-relacionales). 
- Uno de los modelos más importantes es el modelo relacional aparecido en los 70's
- Posteriormente aparecen los llamados sistemas post-relacionales entre los que se encuentran: 
	- Sistema relacional extendido 
	- Sistemas orientados a objetos 
	- Sistemas deductivos
	- Entre otros. 
# Objetivos 
 - Formalización: Permite definir formalmente las estructuras permitidas y las restricciones; establece la base para la definición de un lenguaje de datos y facilita una apreciación más objetiva de la rigidez o flexibilidad de las estructuras de datos, ayudando a la comparación formal de distintos modelos de datos y a la evaluación de los DBMS. 
 - Diseño: Es un elemento fundamental en el desarrollo de una metodología de diseño de bases de datos, en el cuál se basan los otros componentes de la metodología (lenguajes, documentación y otras herramientas); permiten, además, prever el impacto de los cambios del mundo real en el sistema de información. 
# Modelado de Datos 
- Es una de las herramientas que usan los diseñadores de las bases de datos para mostrar la relación lógica entre los datos, la constituye el modelo de datos. El modelado de datos lo constituye un mapa o diagrama de entidades y sus relaciones. 
- Por lo general el modelado de datos incluye la comprensión de un problema de negocios específico y el análisis de los datos y la información necesarios para producir una solución. Cuando se realiza a nivel de toda la organización se denomina modelado de datos de la empresa. 
## Modelado de datos de la empresa
Es un método que se inicia con la investigación de los datos generales y las necesidades de información, a nivel estratégico, de la organización; después lleva a cabo un análisis de las necesidades de datos e información más específicos para las diversas áreas y departamentos funcionales de la organización. 
# Clasificación
- Modelos lógicos basados en objetos: Son una teoría utilizada en la informática que puede describir cómo se relacionan los objetos entre sí y como intercambian información. Estos modelos permiten organizar y estructurar datos de manera que reflejen las propiedades y relaciones del mundo real expresadas en términos de "objetos". Estos objetos representan entidades con atributos y comportamientos. 
	- Almacena datos en objetos en vez de tablas, como lo haría una base de datos relacional. 
	- Este enfoque tiene beneficios en ciertas aplicaciones, ya que permite una representación más natural de los datos y facilita la reutilización y la extensibilidad del código. 
	- **Ventajas de este tipo de modelos**
		- *Encapsulación:* Los detalles internos de los objetos están ocultos y solo se expone una interfaz pública. 
		- *Herencia:* Los objetos pueden heredar propiedades y métodos de otros objetos, lo que permite la reutilización del código. 
		- *Polimorfismo:* Los objetos pueden ser transladados como instancias de su clase más general. 
	- Uno de estos modelos de datos es el conocido como [[Modelo Entidad Relación|MER]]
- Modelos Lógicos Basados en Registros: Son modelo en los que los datos se estructuran en tablas (conocidas como relaciones), donde cada tabla está compuesta de filas (registros o tuplas) y columnas (atributos). 
	- Se utilizan para describir datos en los niveles conceptual y físico. Estos modelos utilizan registros e instancias para representar la realidad, así como las relaciones que existen entre estos registros (ligas) o apuntadores. 
	- **Características y ventajas**
		- *Simplicidad:* Utiliza tablas de datos que son fáciles de entender y usar
		- *Flexibilidad:* Permite realizar consultas complejas utilizando lenguajes de consulta como SQL. 
		- *Integridad de Datos:* Utiliza restricciones y reglas para asegurar la consistencia y correción de los datos. 
		- *Normalización:* Proceso que reduce la redundancia y mejora la integridad de los datos. 
	- Modelo Relacional 
	- Modelo de Red 
	- Modelo Jerárquico
- Modelo físico de datos: Son representaciones detalladas de como los datos se almacenan físicamente en un sistema de base de datos. Estos modelos tienen en cuenta elementos como el hardware utilizado, la capacidad de almacenamiento, el rendimiento, y la organización detallada de los datos en el almacenamiento físico. 
	- Se usan para describir a los datos en el nivel más bajo, aunque existen muy pocos modelos de este tipo, básicamente capturan aspectos de la implementación de los sistemas de base de datos. 
	- Modelo unificador 
	- Memoria de elementos
# Glosario
- Modelo: Es una representación de la realidad que contiene las características generales de algo que se va a realizar. En base de datos, esta representación 
- Proceso de diseño de una base de datos: Conjunto de etapas necesarias para pasar de una determinada realidad a la base de datos que la representa. Los modelos de datos desempeñan un importante papel en el proceso de diseño de una base de datos al ofrecer facilidades de abstracción que ayudan a representar la realidad. 
# Notas 

# Tasks
- [x] Terminar de completar esta nota [[Bases de Datos]] empleando [[2025-01-21]] #task 🔼 ✅ 2025-02-24
# Referencias 
