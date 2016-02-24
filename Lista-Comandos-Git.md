##Lista de comandos útiles para Git

###Para clonar el repositorio de GitHub (sólo una vez):
* `git clone https://github.com/susannalles/MinimalEditions.git`

###Para subir nuevos materiales a GitHub: 
* `git init`: inicia git al interno de la carpeta
* `git add nombre_archivo.txt`: añade el documento (o carpeta) en el area de espera ("stage")
* `git commit -m "mi primer mensaje de cambios"`: describe los cambios realizados
* `git remote add origin https://github.com/susannalles/MinimalEditions.git`: apunta a la dirección donde deseáis subir el nuevo material
* `git push -u origin master"`: subís los cambios al repositorio remote en GitHub por primera vez

###Push & Pull 
* `git add *`: añade el documento (o carpeta) en el area de espera ("stage")
* `git commit -m "mensaje con los detalles del cambio"`: describe los cambios realizados
* `git push origin master`: subís los cambios a GitHub

###Sincronizar nuestra copia con el original:
* `git pull`: baja los cambios del repositorio remoteo a nuestra copia en local 
 
###La Brújula: 
`git status`: señala lo que se ha modificado en la carpeta de trabajo

###Brunches
(Armando)
###Tutoriales & Recursos:
* [Pro Git](http://git-scm.com/book/en/v2) by Scott Chacon and Ben Straub