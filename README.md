# SIGAMI LAMP
Instala automáticamente los programas necesarios para correr un servidor Web en una Máquina Virtual o en un Servidor Privado Virtual (VPS).

Crea o Destruye sitios con sus respectivos archivos de configuración

Instala WordPress Instantaneamente
## Software que Instala
- Apache. 2.4.10  
- PHP 5.6.4
- MySQL 5.5.40
- WP-CLI latest
- /etc/apache2/conf-available/sigami.conf

## Requerimientos
### En el Anfitrión
* VirtualBox o Parecido
* Openssh-Server

     Si es Windows Cygwin o parecido. 
     
     En Ubuntu o parecido `apt-get install openssh-server`

### En máquina virtual o VPS
* Ubuntu Server 14.04
* sigami_lamp

### Instalación
`sudo curl -0 https://raw.githubusercontent.com/sigami/sigami_lamp/master/sigami_lamp >> /usr/local/bin/sigami_lamp && chmod +x sigami_lamp`

`sudo sigami_lamp`

A partir de este momento se te preguntará que hacer, exiten varias diferencias entre un servidor local y uno en vivo los cuales puedes ver aqui: porximamente....

TODO
phpmyadmin, ajenti, postfix, vma, roudcube, ssl para cada una de ellas auto firmado o no

