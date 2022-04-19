# Comando-Linux
Este repositorio es sobre los comandos aprendidos en Sistemas Operativos
Comando | Descripción | Ejemplo de uso |
| ------------- | ------------- | ------------- |
| man  | Despliega un manual  | Al utilizar el comando "man ls" se despliega la página manual para el item ls |
| sudo su  | Ejecuta programas con privilegios de seguridad  | Se usa cuando se necesita tener los privilegios de un usuario (normalmente) "root"  |
| whoami  | Imprime el nombre de usuario  | Este comando tiene como función imprimir el nombre de usuario dado |
| more  | Despliega el resultado de un comando  | Se utuliza para mostrar el resuldato de la ejecución de un comando (normalmente) largo, como puede ser el comando "ls" |
| tail | Lleva al final de un fichero | Se utiliza principalmente paraa no tener que hacer el proceso de llegar hasta el final del fichero de forma manual |
| head | Lleva hasta el inicio de un fichero | Se utiliza principalmente paraa no tener que hacer el proceso de llegar hasta el inicio del fichero de forma manual |
| cp | Copia el contenido de un directorio o fichero | Se utiliza para copiar el contenido de un fichero y poder pasarlo a otra ubicaci+on específica |
| alias | Remplaza cadenas a la hora de ejecutar comandos | Se utiliza para personalizar la interfaz de la terminal de la sesión |
| mv | Mueve o cambia el nombre de archivos y directorios | Se utiliza para mover archivos para que el comando "cp" haga una copia de ellos|
| rm | Elimina archivos | Se utiliza para eliminar el archivo específicado, además puede llegar a borrar directorios|
| useradd | Crea usuarios | Se utiliza para poder crear nuevos usuarios desde la terminal, sin embargo lo crea sin contraseña, directorio ni interprete de comandos |
| passwd | Cambia la contraseña de un usuario | Al utilizar el comando "passwd -a" informa del estado de las contraseñas de los usuarios |
| less | Ver el contenido de un comando | Para ver el contenido de un comando se utiliza "less [option] nome_file" |
| apt install | Instala la versión más nueva de los paquetes solicitados | Para poder descargar el comando "screenfetch" se usa el comando "apt install screenfetch" |
| screenfetch | Recopila información del sistema | Despues de descargar la aplicación mediante el comando "sudo apt intall screenfetch", simplemente se pone el comando "screenfetch" |
| snap | Isntala  programas y comandos | Para descaragar la aplicación Snapcraft, se utiliza el comando " sudo snap install snapcraft --classic." |
| is | Ver archivos y directorios dentro de un directorio | Si utilizamos el comando "Is -a", el comando muestra los archivos y directorios dentro del directorio actual, incluyendo los archivos y directorios ocultos. |
| telnet | Logra una comunicación interactiva con otro host | Mediante el protocolo TELNET, se logra una conexión desde un host a otro|
| ps -aux | Muestra todos los procesos pertenecientes al usuario | Mediante el comando "ps -aux u", se utiliza el formato orientado al usuario|
| ip addr | Muestra el ip del internet que está usando el usuario | Mediante el comando "ip addr" se nos da a conocer información sobre el host y la ip del internet que se utiliza |
| openssh | Conecta la máquina virtual a un servidor | Para cambiar el puerto que se utiliza para estar conectado al servidor, usamos el comando "openssh port (número de puerto que desea usar)" |


Laboratorio #4

Comando | Descripción | Ejemplo de uso |
|`clear`|Limpia el estado actual de la terminal|`clear`|
|`cd`|Cambia el directorio actual|`cd` home/user/Desktop|
|`man`|Muestra el manual para el comando especificado|`man` mkdir|
|`whoami`|Imprime el usuario actual| `whoami`|
|`sudo`|Permite ejecutar un comando como root|`sudo` apt install cmatrix|
|`cp`| Copia el archivo especificado a uno nuevo| `cp` archivo.txt archivo_copia.txt|
|`wget`|Utilidad para descargar archivos de la web|`wget` -q https://packages.microsoft.com/keys/microsoft.asc|
|`pacman`|Administrador de paquetes para distribuciones basadas en Arch| `sudo pacman -Syuu`|
|`useradd`|Crea un nuevo usuario que incluye un directorio de inicio personal| `sudo useradd -m newUser -G rueda -p 123456`|
|`touch`|Crea un nuevo archivo| `toca archivo.txt`|
|`mkdir`|Crea un nuevo directorio| `mkdir nuevoDir`|
|`rmdir`|Elimina el directorio especificado| `rmdir -rf nuevoDir`|
|`tree`|muestra una lista en forma de árbol del directorio y subdirectorios actuales| `árbol`|
|`ls`|Enumera el archivo en la ruta especificada| `ls -l /bin/`|
|`cat`|Imprime el contenido de un archivo dado| `archivo gato.txt`|
|`mv`|Mueve un archivo dado a la ruta especificada, también se puede usar para renombrar| `archivo mv.txt /bin/`|
|`grep`|Útil para buscar dentro de archivos| `grep -rin "registro" /inicio/*`|
|`ps`|Imprime los procesos actuales| `ps -A`|
|`chmod`|Cambia los permisos para el archivo o directorio dado| `chmod 777 archivo.txt`|
|`su`|Si se da un usuario, cambia a él, si no, cambia al usuario root| `su - nuevoUsuario`|
|`pkill`|Mata el proceso dado| `sudo pkill colord`|
|`history`|Imprime todos los comandos usados hasta ahora en la terminal| `historia`|
|`ln`|Crea un enlace duro con el nombre dado al archivo dado. (si se usa -s, crea un enlace suave) | `ln -s /var/log/pacman.log ~/pacman.log`|
|`crontab`|Permite configurar el Daemon crontab| `crontab -e`|
|`nano`|Editor de texto en la terminal| `archivo nano.txt`|
|`vim`|Editor de texto en la terminal| `archivo vim.txt`|
