# Práctica 6

En esta práctica vamos a configurar un RAID 1, consistente en dos disco de igual tamaño, en mi caso serán de 8gb cada uno.

![img](https://github.com/accnono/SWAP1516/blob/master/practica6/img/RAID.png)

Posteriormente creamos el Raid y lo montamos:

![img](https://github.com/accnono/SWAP1516/blob/master/practica6/img/RAID1.png)

![img](https://github.com/accnono/SWAP1516/blob/master/practica6/img/RAID2.png)

y comprobamos el estado del Raid:

![img](https://github.com/accnono/SWAP1516/blob/master/practica6/img/RAID3.png)

Ahora debemos configurar el sistema para que monte el dispositivo RAID creado al arrancar el sistema, para ello primero debemos buscar el UUID del RAID:

![img](https://github.com/accnono/SWAP1516/blob/master/practica6/img/UUIDRAID.png)

Una vez creado y configurado nuestro RAID, vamos a comprobar su correcto funcionamiento provocando un fallo en uno de los discos:

![img](https://github.com/accnono/SWAP1516/blob/master/practica6/img/FALLO.png)

Lo retiramos "en caliente":

![img](https://github.com/accnono/SWAP1516/blob/master/practica6/img/FALLOYRETIRADO.png)

Y lo volvemos a añadir:

![img](https://github.com/accnono/SWAP1516/blob/master/practica6/img/AÑADIDO.png)

Y comprobamos el estado del RAID:

![img](https://github.com/accnono/SWAP1516/blob/master/practica6/img/ESTADOFINAL.png)
