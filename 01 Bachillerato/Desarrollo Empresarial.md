---
Docente: 
Nivel educativo: 
Grado:
---



>[!temas]+ 
>```dataview
>list 
>where contains(materia, [[Desarrollo Empresarial]])
>```

>[!diario]- Notas diarias
>```list
>from "Notas diarias"
>where contains(relacionado, [[Desarrollo Empresarial]])
>```

>[!done]+ Tareas
>```tasks
>not done 
>description includes [[Desarrollo Empresarial]]
>```