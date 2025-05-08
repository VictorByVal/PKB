Materia:: [[Bases de Datos]]
Relacionado:: [[Modelo Entidad Relación]]
>[!concepto]
>Coordenadas que establecen relaciones entre las instancias de distintas entidades
# Notación 
-  Para establecer cardinalidades de mapeo de entidades se usa la notación (1,1)
- Para establecer cardinalidades fuertes en relaciones, se emplea la notación 1:1
# Clasificación 
1. Uno a Uno (1:1): Una instancia de la entidad A se relaciona con una única instancia de la entidad B, y viceversa. Por ejemplo, una persona tiene un único pasaporte y un pasaporte pertenece a una única persona.
2. Uno a Muchos (1:N): Una instancia de la entidad A se relaciona con múltiples instancias de la entidad B, pero una instancia de la entidad B se relaciona con una única instancia de la entidad A. Por ejemplo, un departamento tiene muchos empleados, pero cada empleado pertenece a un único departamento.
3. Muchos a Uno (N:1): Es el inverso de uno a muchos. Múltiples instancias de la entidad A se relacionan con una única instancia de la entidad B. Por ejemplo, muchos empleados trabajan en un único departamento.
4. Muchos a Muchos (N:M): Una instancia de la entidad A se relaciona con múltiples instancias de la entidad B, y una instancia de la entidad B se relaciona con múltiples instancias de la entidad A. Por ejemplo, un estudiante puede estar inscrito en muchos cursos y un curso puede tener muchos estudiantes.
![[Diagrama de Cardinalidades de Mapeo.excalidraw]]
# Notas
- Para determinar la cardinalidad más fuerte de una relación, se toma la coordenada izquierda (el valor de la izquierda), de cada una de las cardinalidades de la relación, y se juntan en una sola cardinalidad. 