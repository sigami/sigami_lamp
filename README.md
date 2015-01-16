# SIGAMI LAMP

This bash script will add the ondrej repositories for Apache and PHP5.6 then perform a full install.

Will also create an apache configration sigami.conf which contains all necesary data for php5-fpm to work.

And creates and mantains php sites with or without wordpress.

The entire script is in spanish and it is not intended to be translated.

Funcionamiento

Descarga el archivo sigami_lamp, cambia sus permisos y copialo.

chmod +x sigami_lamp
sudo cp sigami_lamp /usr/local/bin/

Instalar Apache PHP5.6 y MySQL

En la Terminal del servidor

sudo sigami_lamp [enter]

En la primera ejecución preguntará que tipo de instalación es la que estas ejecutando, lo que cambia es la estuctura de las carpetas en donde van a estar almacenadas las páginas por ejemplo:

En un servidor vivo, las carpetas estarán /srv/sites en un servidor local las buscará en /srv/mnt .

La idéa de un servidor local es que tengas una maquina virtual funcionando como tal, con ubuntu server instalado, de esta manera podrás montar las carptas de tu computadora en tu servidor local y trabajar facilmente en tus archivos

Hay mucha más documentación que se puede hacer acerca de estas poderosas líneas de código pero por el momento esto será suficiente.

