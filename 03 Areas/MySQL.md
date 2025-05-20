Materia:: [[Bases de Datos]]

> [!concepto]
> 

> [!etimologia]
> 

>[!temas]+ 
>```dataview
>list 
>where contains(materia, [[MySQL]]) or contains(parent, [[MySQL]])
>```

>[!diario]- Notas diarias
>```list
>from "Notas diarias"
>where contains(relacionado, [[MySQL]])
>```

>[!done]+ Tareas
>```tasks
>not done 
>description includes [[MySQL]]
