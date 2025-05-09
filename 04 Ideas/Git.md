
>[!temas]+ 
>```dataview
>list 
>where contains(parent, [[Git]])
>```

>[!diario]- Notas diarias
>```list
>from "Notas diarias"
>where contains(relacionado, [[Git]])
>```

>[!done]+ Tareas
>```tasks
>not done 
>description includes [[Git]]
>```

# Tipos de configuraciones en Git 
1. `git config --system` modifica el archivo ubicado en `[path]/etc/gitconfig` mismo que modifica los valores aplicados a cada usuario en el sistema y todos sus repositorios
	- Dado que es un archivo de configuración de sistema, se necesitará acceso como super usuario o administrador para realizar cambios en dicho archivo. 
2. `git config --global` modifica el archivo ubicado en `[/.config/git/config]` mismo que modifica valores específicamente al usuario. 
3. `git config --local` modifica el archivo ubicado en `.git/config` de cualquier repositorio en el que estés trabajando, lo cuál modifica los ajustes exclusivamente de ese repositorio. 
	- Es necesario que te encuentres dentro de un repositorio para que esta opción funcione propiamente. 

> [!attention]
> Cada nivel de configuración sobre-escribe los valores en el nivel previo, así que el nivel más alto de configuración es el tercero (A nivel local). 

- Para ver todas las configuraciones de git y de donde vienen se emplea: `git config --list --show-origin`

