---
Docente: Hugo Leonardo Martínez Gómez
Nivel educativo: "[[Universidad]]"
Grado: Primer Semestre
---
>[!temas]+ 
>```dataview
List
where contains(materia, [[Teoría del seguro]])
>```

>[!diario]- Notas diarias
>```dataview
>list 
>From "Notas diarias"
>where contains(materia, [[Teoría del seguro]])
>```

>[!todo]+ Tareas
>```tasks 
>not done 
>description includes [[Teoría del seguro]]
>```