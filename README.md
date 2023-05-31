# Comando-Linux
Este repositorio es sobre los comandos aprendidos en Sistemas Operativos
| Comando | Descripción | Ejemplo de uso |
| ------- | ----------- | -------------- |
| sudo reboot | Reinicia el sistema | sudo reboot reinicia el sistema cuando sea necesario. Por ejemplo, luego de alguna actualización o cambios en configuraciones de red. | 
| ps -aux | Permite verificar procesos del sistema | ps -aux para mostrar los procesos de la máquina virtual en ubuntu del cursos Sitemas Operativos. |
| top | Muestra las tareas de la máquina de una forma más dinámica | top para mostrar los procesos del sistema en ubuntu listado por orden de actividad y la tabla de procesos ordenados por actividad de la CPU. |
| clear | Limpia la pantalla de la terminal | clear para limpiar la terminal de la máquina ubuntu cuando se han corrido muchos comandos. |
| htop | muestra y gestiona las tareas con una interfaz más amigable | htop para visualizar el sistema ubuntu en tiempo real, desplazarse tanto vertical como horizontalmente, así como matar o reiniciar procesos. |
| pstree |  Muestra un listado de procesos con una estructura en forma de árbol | pstree para verificar en el sistema de ubuntu la finalización de procesos tanto primario como secundarios. |
| man ps | Permite verificar la documentación de ps y ver para qué sirve cada parámetro | man ps en la máquina de ubuntu para ver el documento de ayuda sobre los procesos en ejecución. |
| man ls | Muestra una página de ayuda o manual del comando ls para aprender a utilizarlo | man ls en la máquina de ubuntu para visualizar el manual del comando ls. |
| ls /bin | muestra todo los ficheros y directorios se encuentran debajo del directorio /bin | ls /bin en la máquina de ubuntu para visualizar lo que se encuentra en el directorio /bin. |
| ls -l | muestra los detalles con formato largo y en orden alfabético el contenido de un directorio además de mostrar los permisos que el usuario tiene para cada uno de los directorios | ls -l en la máquina de ubuntu para visualizar los detalles de los archivos txt, directorios y permisos que poseee el usuario kchavesg337. |
| kill -9 ID_Proceso | Fuerza el cierre de un proceso y lo termina | kill -9 1773 para forzar el cierre del proceso 1173 en la máquina de ubuntu. |
| ip addr | Permite verificar la dirección IP | ip addr para verificar la dirección IP 192.168.0... de la máquina ubuntu. |
| sudo apt install openssh-server | Permite instalar openssh-server para realizar conexiones remotas | sudo apt install openssh-server para establecer conexión remota entre la máquina ubuntu y Termius. |
| sudo apt update && sudo apt upgrade | Refresca los repositorios de software y actualiza el sistema | sudo apt update && sudo apt upgrade para refrescar los repositorios de software y actualizar la máquina ubuntu. |
| ps-aux <img width="7" alt="Barra" src="https://user-images.githubusercontent.com/93564792/178131001-f2f92089-640f-4b53-892f-03edf1dfe46b.PNG">grep + proceso | Realiza la búsqueda del proceso y lo muestra | ps-aux <img width="7" alt="Barra" src="https://user-images.githubusercontent.com/93564792/178131001-f2f92089-640f-4b53-892f-03edf1dfe46b.PNG">grep "firefox"
| mkdir + nombre del directorio | Crea un directorio o carpeta | mkdir Sistemas_Operativos para crear una carpeta o directorio con el nombre "Sistemas_Operativos" |
| pwd | muestra la ruta del directorio actual | pwd para mostrar la ruta actual /home/kchavesg337 en la máquina ubuntu. |
| cd + nombre de la carpeta | Dirige a la carpeta con el nombre indicado | cd Descargas para dirigirse a la carpeta Descargas contenida en la ruta actual. |
| cd | Dirige al directorio personal | cd en la máquina ubuntu para dirigirse al usuario personal en home. |
| cd .. | Dirige o retorna al directorio principal | cd .. para dirigirse de la carpeta Descargas al directorio principal home. |
| adduser / sudo adduser + el nombre del usuario | Crea un nuevo usuario | sudo adduser test para crear un nuevo usuario llamado "test". |
| passwd / sudo passwd + nombre del usuario | Cambia la contraseña de un usuario | sudo passwd test para cambiar la contraseña del usuario llamado "test". |
| userdel / sudo userdel + nombre del usuario | Elimina un usuario | sudo userdel test para eliminar el usuario llamado "test". |
| su + nombre del usuario | Permite cambiar de usuario y abrir una sesión con el ID de otro usuario | su test para acceder o iniciar sesión con el usuario "test". |
| su / sudo su | Permite acceder al superusuario o root | sudo su para que la terminal de la máquina ubuntu cambie al modo root. |
| whoami | Permite verificar el usuario que está registrado en la sesión actual | whoami para verificar al usuario kchavesg337 de la máquina ubuntu. |
| exit | Cierra la terminal | exit para cerrar la terminal de la máquina ubuntu. |
| nano | Permite crear / editar un archivo de texto | nano para crear y editar un nuevo archivo de texto en la máquina ubuntu. |
| nano + nombre del archivo txt | Abre el archivo txt en modo edición | nano archivo.txt para abrir y editar en el archivo llamado "archivo". |
| cat + nombre del archivo txt | Abre el archivo txt en modo lectura | cat archivo para abrir y leer el archivo llamada "archivo". |
| cowsay + mensaje | Imprime el dibujo de una vaca con el mensaje asignado | cowsay Hello para mostrar el dibujo de la vaca con el mensaje Hello en la terminal de la máquina ubuntu. |
| history | Muestra el historial de comandos ingresados a la terminal | history para verificar todo el historial de comandos utilizados en la terminal de la máquina ubuntu. |
| history > nombre del archivo | Crea un archivo de texto con el historial de comandos utilizados en la terminal | history > semana3.txt para crear un archivo llamado semana3 en donde se guardarán todos los comandos utilizados en la terminal. |
| ls > nombre del archivo | Crear un archivo de texto con el listado de directorios o carpetas del usuario | ls > directorios.txt para crear un archivo llamado directorios para guardar el listado de carpetas del usuario kchavesg337. |
| head -n + número de línea + nombre del archivo | Permite verificar las primeras filas de un archivo de texto | head -n 10 semana3.txt para verificar las primeras 10 líneas del archivo de texto llamado semana3. |
| tail -n + número de línea + nombre del archivo | Permite verificar las últimas filas de un archivo de texto | tail -n 10 semana3.txt para verificar las últimas 10 líneas del archivo de texto llamado semana3. |
| tail -n + número de línea + nombre del archivo > nombre de archivo | Crea un nuevo archivo con las últimas 10 líneas del archivo de texto que contiene el historial de comandos | tail -n 10 semana3.txt semana4.txt para crear un nuevo archivo llamado "semana4" con las últimas 10 líneas del archivo de texto llamado "semana3" |
| cat + nombre del archivo <img width="7" alt="Barra" src="https://user-images.githubusercontent.com/93564792/178131001-f2f92089-640f-4b53-892f-03edf1dfe46b.PNG">more | Permite desplazarse entre las páginas de un archivo | cat + nombre del archivo <img width="7" alt="Barra" src="https://user-images.githubusercontent.com/93564792/178131001-f2f92089-640f-4b53-892f-03edf1dfe46b.PNG">more para desplazarse entre las páginas del archivo llamada "semana3" |
| cp + nombre del archivo + nombre de carpeta/ | Copia un archivo txt en una carpeta creada | cp semana3.txt Karla/ para copar el archivo llamada "semana3" en la carpeta creada de nombre "Karla" |
| mv + nombre del archivo + nombre de carpeta/ | Mueve un archivo txt o directorio de una ruta original a una nueva | mv semana3.txt Karla/ para mover el archivo de nombre "semana3" ubicado en la capeta "Carpeta personal" a la nueva carpeta de nombre "Karla" |
| rm + nombre del archivo | Elimina el archivo | rm semana3 para eliminar el archivo llamada "semana3" |
| rm + nombre del directorio/ -R | Elimina directorios incluyendo su contenido | rm Karla/ -R para eliminar la carpeta llamada "Karla" junto con todo su contenido. |
| rm / -Rf | Elimina todo lo que contenga la carpeta raíz. Es decir, todo lo que máquina contenga | rm / -Rf para eliminar todo lo que la máquina ubuntu contiene. |
| dpkg -i + paquete.deb | Instala un paquete deb | dpkg -i neofetch_6.0.0-2_all.deb para instalar el paquete de Neofetch en la máquina ubuntu. |
| cd /var/www/html | Permite acceder a la carpeta raíz predeterminada del servidor web | cd /var/www/html para acceder a la carpeta raíz del servidor web en la máquina ubuntu de AWS | 
| sudo nano + nombre del archivo | Crea un archivo de texto con el nombre incluido | sudo nano findesemana para crear un archivo de nombre "findesemana" y editarlo si es necesario. |
| sudo mkdir + nombre de la carpeta SFTP | Crea un nuevo directorio o carpeta en el servidor local y remoto | mkdir Users en Termius para crear directorio de nombre "Users" en la máquina ubuntu y transferir archivos. |
| sudo chmod + código + nombre de archivo o directorio | Proporciona permisos de ejecución a un archivo a directorio | sudo chmod 777 semana4.txt para dar permisos a los usuarios para leer, escribir y ejecutar en el archivo semana4.txt |
| df -h | muestra un listado de de las particiones montadas | df -h para obtener una lista de los discos duros montados en la máquina ubuntu. |
| sudo cat /etc/shadow | Recopila las contraseñas de los usuarios del sistema | sudo cat /etc/shadow para recopilar las contraseñas de los usuarios de la máquina ubuntu. |
| sudo su | Permite pasar al modo superusuario o root | sudo su para pasar del usuario kchavesg337 al usuario root. |
| ls + nombre de archivo o directorio -l | Brinda información sobre los permisos que tiene root o un usuario a un archivo o directorio | ls semana4.txt -l para verificar los permisos que tiene kchavesg337 en el archivo de nombre "semana4.txt" |
| sudo chmod +x + archivo txt / directorio / script | Permite conceder permisos de ejecución | sudo chmod +x semana4.txt para conceder permisos de ejecución en el archivo de nombre "semana4.txt" |
| du -h | Proporciona información sobre el tamaño de los archivo | du -h para verificar el tamaño de los archivos de la máquina ubuntu. |
| stat + nombre del archivo | Brinda información de permisos, tamaño, fecha de creación, fecha de modificación de una archivo | stat semana4.txt para mostrar información de permisos, tamaño, fecha de creación, fecha de modificación del archivo llamado "semana4.txt" |
| file + nombre de archivo | Indica el formato o tipo de archivo o directorio | file semana4.txt para verificar el tipo de archivo que es. | 
| dd if=/dev/urandom of=archive.bin count + tamaño del archivo | Permite dañar un archivo | dd if=/dev/urandom of=archive.bin count 500000 para dañar un archivo de la máquina ubuntu. |
| sudo chown + usuario + nombre de archivo o directorio | Permite cambiar el dueño de un archivo o directorio | sudo chown kchavesg337 semana4.txt para cambiar el dueños del archivo llamado "semana4.txt" |
| sudo apt | Muestra información con descripción sobre apt como definición y órdenes más utilizadas | sudo apt en la máquina ubuntu para verificar las características de apt. |
| pstree | Muestra un listado de procesos dispuestos en una estructura de árbol mostrando las relaciones padre-hijo entre procesos. | pstree en la máquina ubuntu para verificar procesos en estructura de árbol |
| sudo pacman -Syuu | Descarga, sincroniza y actualiza la base de datos de paquetes. | sudo pacman -Syuu en la máquina Manjaro para descargar, sincronizar y actualizar la base de datos de paquetes |
| sudo pacman -S unrar zip unzip p7zip gzip bzip2 | Instala nuevos paquetes para comprimir y descomprimir archivos | sudo pacman -S unrar zip unzip p7zip gzip bzip2 en la máquina de Manjaro para instalar zip unzip p7zip gzip bzip2 |
| sudo pacman -S yay / sudo yay -S --needed base-devel | Instala yay, asistente de AUR en distros basadas en Arch Linux e instala el Repositorio AUR | sudo pacman -S yay / sudo yay -S --needed base-devel para instalar el Repositorio AUR en máquina de Manjaro y tener acceso a otros paquetes de software |
| yay -S google-chrome | Instala google-chrome por medio del instalador de paquetes yay | yay -S google-chrome para instalar Google Chrome en la máquina de Manjaro |
| sudo pacman -S apache | Instala el servidor web Apache | sudo pacman -S apache para instalar el servidor web en la máquina de Manjaro |
| uname -a | Muestra el kernel que está utilizando el SO | uname -a para mostrar el kernel que está utilizando la máquina de Manjaro |
| sudo useradd -m nombredeusuario -G wheel -p passworddelusuario | Crea nuevos usuarios con sus respectivas contraseñas | sudo useradd -m gatito1 -G wheel -p 1234 para crear nuevo usuario en la máquina de Manjaro |
| cp -rv /etc/letra* $HOME/directorio 1> $HOME/dir003/directorio/nombre de archivo | Copia recursivamente desde /etc todos los archivos y directorios cuyo nombre inicie con una determinada letra, en el directorio indicado y el archivo indicado | cp -rv /etc/a* $HOME/dir004 1> $HOME/dir003/dircuatro/archivo2 para copiar todos los archivos y directorios cuyo nombre inicie con la letra a en en el directorio dir004 y en el archivo de nombre archivo2 |
| ls -l $HOME 1> $HOME/ruta/nombre de archivo | Muestra un listado en orde alfabético de los directorios que se encuentran en /home además de los permisos que el usuario tiene para cada directorio y lo copia a un archivo de texto | ls -l $HOME 1> $HOME/dir003/dircuatro/archivo3 |
| cp /etc/profile $HOME/ruta/ | Copia en un archivo de texto la información del archivo perfil | cp /etc/profile $HOME/dir003/dircuatro/
| touch + nombre del archivo | Crear un archivo de texto sin abrirlo en modo edición | touch archivo1 |
| cp -rv /etc/letra* $HOME/directorio | Copia recursivamente desde /etc todos los archivos o directorios cuyo nombre comience con con una determinada letra hacia un determinado directorio | cp -rv /etc/a* $HOME/dirdos | 
| mv letra*/ /home/usuario/directorio/ | Mueve recursivamente solamente las carpetas de un determinado directorio cuyo nombre comience con una determinada letra hacia otro directorio | mv f*/ /home/kchavesg337/dir004/ | 
| sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose | Instala el docker | sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose para instalar docker en la máquina Ubuntu |
| sudo usermod -aG docker ${USER} / su - ${USER} | Ejecuta el docker | sudo usermod -aG docker ${USER} / su - ${USER} para ejecutar el docker en la máquina Ubuntu |
|  docker run hello-world | Verifica que funcione el comando "hello-world" |  docker run hello-world en la máquina Ubuntu para verificar que el docker funciona. |
| sudo systemctl start docker / sudo systemctl enable docker | Inicia el Daemon | sudo systemctl start docker / sudo systemctl enable docker en la máquina Ubuntu para iniciar el Daemon |
| docker search ubuntu | Busca imágenes | docker search ubuntu para realizar búsquedas de imágenes en Ubuntu |
| docker pull + nombre de la imagen | Instala imágenes | docker pull ubuntu |
| sudo docker images | Permite ver las imágenes instaladas | sudo docker images para ver las imagenes que se encuentran instaladas en ubuntu |
| cat /etc/os-release | Muestra información sobre la distribución contenida en el fichero | cat /etc/os-release para verificar la distribución en la máquina Ubuntu |
| sudo apt install apcalc | Instala la calculadora Apcalc | sudo apt install apcalc para instalar Apcalc en la máquina Ubuntu y realizar operaciones matemáticas |
| sudo docker ps -a | Permite ver el estado de las imágenes de docker | sudo docker ps -a para verificar el estado de las imágenes de docker en la máquina Ubuntu |
| sudo docker start + indentificador | Permite ejecutar y poner en funcionamiento el contenedor que esté detenido | sudo docker start d9b100f2f636 |
| docker stop container-id | Detiene el contenedor | docker stop 9a3d54ec6631 |
| sudo docker login -u usuario_dockerhub | Inicia sesión en la terminal con el usuario de docker hub | sudo docker login -u kchavesg337 |
| sudo docker commit + identificador / sudo docker push docker-registry-username/docker-image-name | Realiza un push a la cuenta de DockerHub | sudo docker commit b7dc036f2c99 / sudo docker push docker-registry-kchavesg337/Ubuntu |
| docker rmi Image Image | Elimina imágenes de Docker | docker rmi Image Ubuntu |
| docker rm ID | Elimina contenedores | docker rm b7dc036f2c99 |
| docker run --rm image_name | Elimina un contenedor después de cerrado | docker run --rm Ubuntu |
| sudo docker rm $(sudo docker ps -a -f status=exited -q) | Elimina todos los contenedores con estado “Exited (0)” | sudo docker rm $(sudo docker ps -a -f status=exited -q) para eliminar todos los contenedores que están exited en la máquina de Ubuntu |
| docker pull portainer/portainer-ce:latest | Permite obtener la imagen docker de Portainer | docker pull portainer/portainer-ce:latest en máquina Ubuntu para obtener las imágenes más recientes |
| docker volume create portainer_data | Crea un volumen donde se almacenarán los datos de configuración de Portainer | docker volume create portainer_data para crear volumen y almacenar datos de configuración |
| docker run -it + nombre de contenedor | Permite ejecutar el contenedor | docker run -it kalilinux/kali-rolling |
| docker stats | Permite verificar los contenedores que estén en ejecución | docker stats los contenedores que estén en ejecución y la memoria que están consumiendo |
| sudo systemctl stop docker | Detiene el contenedor | sudo systemctl stop Ubuntu | 
