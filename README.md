# Comandos Linux SO

Si se quiere autocompletar un comando es necesario escribir unas cuantas letras del comando y apretar *TAB*.
Con la flecha de arriba se muestran los comandos anteriores que se han digitado en la terminal.
En Linux la instalación de los programas se hace con **sudo apt install** nombrePrograma
Los comandos en Linux se escriben de primero, si hay algo más después del comando viene siendo el parámetro. Los parámetros modifican al comando

## Comandos Linux

**pwd**: Muestra la ruta en la cual nos encontramos.

**sudo**: Da permisos de administrador a un comando. 

**sudo apt update**: Actualiza los paquetes (repositorios) a los últimos.

**apt**: es el comando que permite actualizar software de los repositorios.

**clear**: limpia la terminal.

**sudo apt search *nombreAplicación***: Realiza una búsqueda del nombre de la apliación para ver si se encuentra.

**lsb_release -a**: Muestra la versión del sistema operativo.

**uname -a**: Indica cuál es la versión del Kernel de Linux que se está utilizando.

**mkdir *nombreDirectorio***: Permite crear un directorio o carpeta.

**ls**: Muestra los archivos o carpetas que se encuentran dentro del directorio en el que nos encontramos. En otras palabras, lista directorios.

**ls -l**: Lista los archivos, mostrando el nombre, fecha de modificación de un archivo, el usuario dueño, entre otros.

**man**: Llama al manual.

**man -ls**: lista todos los comandos que se encuentran en el manual.

**ip addr**: permite visualizar la dirección ip del dispositivo y los adaptadores.

**pin *direcciónIp***: Permite probar la conectividad con otros equipos.

**sudo apt install openssh-server**: Instala el paquete de SSH. El protocolo SSH es un protocolo para transferencia de archivos y para hacer consola remota (conexiones de equipos desde otras máquinas). Es necesario instalar este servicio para poder abrir el puerto necesario para la conexión.

**Sudo apt install nmap**: Realiza la instalación de nmap el cual permite verificar que el equipo tenga el servicio levantado.

**Nmap *direcciónIp***: Indica cuales puertos se encuentran abiertos y cual servicio se está utilizando en el puerto abierto. (antes de utilizar esto es necesario instalar nmap)

**cd *nombreCarpeta/directorio***: Permite un movimiento a la carpeta que se especifique y que se encuentre dentro de la misma ruta o directorio.

**cd ..** : Retrocede a la carpeta o ruta anterior.

**touch *nombreArchivo.extensión***: Permite crear un archivo sin contenido.

**nano *nombreArchivo.extensión***: Permite editar un archivo.

**cat *nombreArchivo.extensión***: Muestra el contenido de un archivo en la terminal.

**more *nombreArchivo.extensión***: Muestra el contenido de un archivo en la terminal.

**les *nombreArchivo.extensión***: Muestra el contenido de un archivo en la terminal.

**cat /etc/passwd**: Muestra todos los usuarios que están registrados en el sistema.

**ps -aux**: Muestra todos los procesos que se están ejecutando.

**top**: Muestra todos los procesos que se están ejecutando, pero es más interactivo y es en tiempo real, así como algunos datos de memoria del dispositivo.

**pstree**: Es otra forma de ver los paquetes o procesos en forma como de un árbol, procesos padres y sus hijos.

**htop (es necesario instalarlo)**: Otra forma de ver los procesos en tiempo real, así como los comandos que se están ejecutando en cada proceso.

**grep**: Comando para buscar texto en cualquier lugar.

**kill -9 *númeroProceso* (el proceso se puede ver con ps -aux | grep nombreProceso)**: Mata el proceso seleccionado, o sea, cierra la aplicación que se definió. 

**root**: Es el usuario administrador, que tiene todos lo permisos en el sistema operativo.

**su root**: Permite iniciar sesión como administrador.

**sudo su**: Otra forma de iniciar sesión como administrador.

Para establecer la contraseña del usuario *root* se pone **sudo passwd root**. Si se quiere salir del usuario root se pone *exit*.

**whoami**: Permite saber con cual usuario nos encontramos.

**fish**:Cambia a la consola fish.

**sudo apt install samba**: Instala el servico de smb.

**adduser *nombreUsuario***: Para agregar un nuevo usuario.

**sudo apt-get install xubuntu-desktop**: Instala el entorno XFCE.

**apt install xfce4 xfce4-goodies tightvncserver**: Instalación del servicio VNC.

**sudo apt install ufw -y**: Instalación del Firewall.

**sudo apt install vsftpd**: Instalación de FTP.

**nano *nombreArchivo***: Permite editar un archivo de texto.

**sudo apt-get install squid -y**: Instalación de Proxy.

**sudo apt install -y apache2**: Instalación de Apache.

**sudo systemctl enable apache2**: Habilita el arranque de Apache.

**sudo apt install mariadb-server mariadb-client -y**: Instalación de MariaDB.

**ll**: Permite visualizar los permisos de los archivos dentro de una ruta.

**sudo apt install easy-rsa ssh openvpn**: Instala el servicio de OpenVPN.



## Manjaro

 1. Actualización de paquetes del sistema operativo Manjaro: **sudo pacman -Syuu**

2. Instalación del repositorio AUR en Manjaro: **sudo pacman -S yay | sudo yay -S --needed base-devel**

3. Para descargar paquetes con Aur: **yay -S nombreDelPrograma**

**Chmod**: permite la modificación de permisos de los archivos.
**Chown**: permite cambiar de propietario archivos o directorios.
**Rmdir**: elimina directorios o carpetas.
**Rm**: elimina archivos.

**crontab -e** : crea un nuevo proceso o tarea a ejecutarse según el lo que se defina en cron

**crontab -l**: lista los procesos crontab que existen.

## Docker

**images**: Visualiza las imágenes que tenemos.

**docker ps -a**: Contenedores de Docker que tenemos disponibles.

**docker info**: Sistemas de ficheros info.

**docker network ls**:Redes en Docker.

**docker pull**: Para descargar imágenes en Docker.

**Docker run -ti –rm**:Para borrado automático de los contenedores.
