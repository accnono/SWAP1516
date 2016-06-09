# Práctica 2

Depués de insertar las "keys" para el acceso autmático a través de ssh realizamos el siguiente archivo de tareas crontab:

![img](https://github.com/accnono/SWAP1516/blob/master/practica2/crontab.png)

Donde podemos observar cada uno de los parámetros que indican que la tarea se ejcutará cada hora en punto, todos los días de todos los meses.
Además indicamos el usuario (root) y la tarea:

rsync -e ssh root@172.16.123.131:/var/www/ /var/www/

Por lo que vamos a clonar el contenido de la carpeta /var/www/ del servidor 1 en el servidor 2.
