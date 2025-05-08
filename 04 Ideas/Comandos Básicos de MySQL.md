---
aliases: 
tags:
---
Materia:: [[Bases de Datos]]
Subtema:: [[MySQL]]
Relacionado:: 

# CRUD 
## Create 
Para crear cosas se emplea el comando `create`
```MySQL 
create table <Nombre de la tabla>
(<Nombre del atributo> <Tipo de dato> <Restricciones>, 
... 
<Nombre del atributo> <Tipo de dato> <Restricciones>); 
```
algunos de los parámetros del comando son: `database` para crear una nueva base de datos, `table` para tablas. 
# Read 

# Update 

# Delete 

# Alter 
Se emplea `alter table` para modificar atributos  de una tabla y no tener que volver a empezar de cero botando la tabla. posteriormente se puede emplear un conjunto de comandos como `alter`, `drop`, `rename`, `modify` o `add` en conjunto con el parámetro `column` para alterar de distintas formas las columnas, hay que tomar en cuenta que el comando modify y alter hacen lo mismo para las columnas, lo único que varía es que dichos comandos no son usables en todas las versiones de MySQL. 

# Otros comandos 
Se emplea el comando `enum` para alternar entre distintas etiquetas y poner una etiqueta por default: 
```MySQL 
<atributo> enum ("<Etiqueta 1>", "<Etiqueta 2>" , ... , "<Etiqueta 3>") Default "<Etiqueta 1>"
```

Se emplea `distinct`  para enumerar solo los datos que sean distintos unos de otros. 
