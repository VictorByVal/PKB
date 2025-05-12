---
Docente: 
Nivel educativo: "[[Universidad]]"
Grado: Primer Semestre
---



>[!temas]+ 
>```dataview
>list 
>where contains(materia, [[Introducción a a la Programación]])
>```

>[!diario]- Notas diarias
>```list
>from "Notas diarias"
>where contains(relacionado, [[Introducción a la Programación]])
>```

>[!done]+ Tareas
>```tasks
>not done 
>description includes [[Introducción a la Programación]]
>```