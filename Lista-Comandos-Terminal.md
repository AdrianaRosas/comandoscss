##Lista de comandos útiles para el terminal

###¿Para qué sirve el terminal?

Línea de comandos o terminal es una interfaz de texto en la que pueden escribirse reglas o comandos que el ordenador debe llevar a cabo. Muchas de las tareas que realizamos cotidianamente son realmente más eficaces si las llevamos a cabo con el terminal, especialmente en relación a los derechos de los archivos. 

Desde el terminar podemos realizar diferentes tareas, como listar nuestros documentos, navegar a través de nuestros ficheros, crear nuevos archivos y carpetas, ejecutar programas, escribir scripts de complejidad variable, etc.

En el MAC, el terminal se sitúa en Applicaciones > Utilities > Terminal. 

(N.B. Si no os gusta el color negro, podéis personalizarlo a vuestro gusto).
 
El símbolo $ (shell prompt) indica que el terminal está listo para recibir órdenes y que ya puedes escribir en la interfaz. 


###Sistema de ficheros (filesystem)

Antes de nada, es preciso que conozcas el funcionamiento del sistema de ficheros _file system_) de tu máquina, es decir, cómo organiza las directorios (o carpetas, _folders_) y los archivos (o documentos, _files_).

La estructura es siempre arbórea: hay un directorio raíz (_root directory_) y, a partir de él, encontramos los descendientes (_children_). [Ejemplo](https://s3.amazonaws.com/codecademy-content/courses/learn-the-command-line/img/LCL-fileTrees-01.png)

Para navegar a través de tus directorios y ficheros, hay una serie de comandos necesarios: 

* pwd - print working directory - indica en qué directorio te encuentras
* ls - list - lista los directorios y archivos de tu ubicación
* cd - change directory -  se utiliza para cambiar de directorio
* cd nombre_del_directorio - navega hacia un directorio descendiente
* cd ../ - sube un directorio
* cd ../../ - sube dos directorios
* cd / - va al directorio raíz de tu ordenador
* mkdir - make directory - crea un directorio 
* touch - crea un nuevo file en el directorio donde te encuentras (acordaros de poner siempre la extensión)
 
Veamos ahora la lista de comandos para manipular los ficheros (mover, cortar, borrar) 

* ls -a - lista todos los ficheros, incluso los que están ocultos que empiezan por un .
* ls -l - lista todos los ficheros de un directorio en un formato largo


