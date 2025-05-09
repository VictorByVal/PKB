
Parent:: [[Git]]

# Identidad 
Lo primero que se debe realizar es fijar el nombre de usuario y la dirección de correo, esto es importante debido a que cada commit que Git realiza usa esta información, y es inmutablemente copiado en cada commit que se realiza: 
```git 
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com 
```

Solo se necesitará realizar esto una sola vez si es que se pasa la opción `--global` verificar [[Niveles de Configuración en Git]] para cualquier duda al respecto. 

# Editor 
Se puede modificar el editor de texto por defecto que Git va a abrir cada que se deba escribir el mensaje para un commit 
```git 
$ git config --global core.editor emacs 
```

en el caso de los sistemas windows se debe especificar el path completo al archivo ejecutable, lo cual puede variar dependiendo de como tu editor esta empacado. 
```git 
$ git config --global.core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
```

# Nombre de la rama por Default 
Por default Git creará una rama `master` cuando se creen nuevos repositorios con el comando `git init`, no obstante se puede alterar esto a partir de la versión 2.28 en adelante. 
```git
$ git config --global init.defaultBranch main
```
El comando anterior cambia la rama por default a `main` y lo hace de manera global para todos los repositorios del usuario. 

