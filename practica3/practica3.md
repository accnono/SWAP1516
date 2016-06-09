#Práctica 3

En esta practica configuraremos 2 balanceadores de carga, ngix y haproxy, además de un tercero pound.

La práctica está defendida en clase con D.Pedro A, Castillo, por lo que no adjunto capturas de pantalla.

Para activar el primero deberemos ejecutar el comando:

  service nginx start

Para desactivarlo:

  service nginx stop

Funciona correctamente.

El segundo balanceador, haproxy, en cambio se activa del siguiente modo:

  /usr/sbin/haproxy -f /etc/haproxy/haproxy.cfg

Y para desactivarlo deberemos "matar" el proceso.

Tamién se encuentra en perfecto funcionamiento.

Finalmente, como balanceador optativo decidí escoger pound, después de una pequeña configuración, a pesar de algo "oscura" al principio, logramos montar le servicio y lanzarlo con la siguiente orden:

  service pound start

y para desactivarlo:

    service pound stop

  Funciona correctamente.
