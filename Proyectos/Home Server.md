---
aliases:
  - Homelab
tags:
---
Relacionado:: [[Study System]]

```ad-abstract
title: Resumen 
La idea consiste en crear un servidor casero de la manera más barata, sencilla, pero a la vez duradera y escalable posible, para ello la opción que se me ocurre es comprar una Raspberry pi, quizá junto con alguna SD y un case, para conectarla a la red Wifi directamente por cable Ethernet. 
```

# Motivos 
- Alojar música debido a que me encuentro en el dilema, de querer disponer de mi música sin tener que estarla stremeando o accediendo a ella desde servidores desconocidos. 
- Obtener un crecimiento personal al poder conocer más acerca de esa área y la manera en la que se mueve. 
# Tareas 
- [ ] Informarme acerca de los modelos de Raspberry Pi, sus características y con que elementos cuenta #task 
	- En específico debo concentrarme en el sistema operativo, si puede resistir la instalación de PROXMOX
- [ ] Investigar más programas open source para tener contemplados en un servidor local. #task 
# Lista de programas a considerar 
1. PROXMOX: Para realizar la gestión de contenedores y almacenar ahí distintos tipos de sistemas operativos. 
2. Jellyfin: Para gestionar un servidor multimedia, hosteado por mi mismo, en el que pueda contar con archivos personales, desde música hasta películas y demás. 
3. Docker: Para realizar la gestión de contenedores y almacenar ahí distintos programas. 
4. Bitwarden: Para tener mis contraseñas en un servidor privado, desde el cual pueda acceder a ellas 
5. Nextcloud, Owncloud o Seafile: Para generar servicios de nube privados autohosteados. 
# Aproximaciones 
## Instalar sobre el propio sistema 
- [Esta página web](https://pimylifeup.com/raspberry-pi-jellyfin/) tiene instrucciones muy detalladas sobre como instalar jellyfin directamente en ubuntu o el propio sistema operativo de la Raspberry Pi (Raspberry Pi OS). 
## Virtualización 
### Virtualización a través de PROXMOX
#### Consideraciones a tomar en cuenta 
1. PROXMOX no esta oficialmente soportado para funcionar en una Raspberry Pi, y por consiguiente ninguno de los programas que corras en cualquiera de sus maquinas virtuales, pero lo soportan, en el [siguiente video](https://youtu.be/VbWd-bWhg9I?si=kSlpy-I2EWO7AsJY) encontré información útil acerca de la instalación de PROXMOX en una Raspberry Pi 
#### Seguridad y detalles adicionales 
- Si voy a tener un servidor propio, creo que lo mejor sería empezar a pensar en un sistema tipo NAS, para mantener los archivos y datos dentro del servidor lo más seguros posibles [esta página](https://www.serverwatch.com/storage/free-nas-solutions/) tiene comparaciones entre los distintos tipos de software NAS. 
