---
Docente: 
Nivel educativo: 
Grado:
---



>[!temas]+ 
>```dataview
>list 
>where contains(materia, [[Ecología y medio ambiente]])
>```

>[!diario]- Notas diarias
>```list
>from "Notas diarias"
>where contains(relacionado, [[Ecología y medio ambiente]])
>```

>[!done]+ Tareas
>```tasks
>not done 
>description includes [[Ecología y medio ambiente]]
>```