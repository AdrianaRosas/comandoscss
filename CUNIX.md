##Indicaciones para conectarse al servidor de Columbia: CUNIX

Nos conectaremos al servidor de Columbia con vuestro uni. Abrid el terminal y escribid lo siguiente: 

   `$ ssh vuestroUNI@cunix.columbia.edu`

Os preguntará vuestra contraseña y deberéis escribirla (aunque el cursor no se mueva). ¡Ya estáis dentro!

Practicad algunos comandos básicos:

     `$ pwd`
     `$ ls`

Si no lo tenéis ya, deberemos crear un directorio nuevo que se llamará `public_html`:

     `$ mkdir public_html`

Nos situamos dentro: 
     `$ cd public_html`

Ahora, creemos un fichero nuevo: 

     `$ pico nombre_fichero.txt`

Para ver los permisos de un fichero:
     `$ ls –l` 

Debermos cambiar los permisos para que pueda ser leído por todos:

     `$ chmod a+rx nombre_fichero.txt`

Ahora debéis ir a la dirección:

     `$ http://www.columbia.edu/~UNI/nombre_fichero.txt`

Ahora repetimos la operación creando un fichero .html que va a llamarse `index.html`: 

    '$ pico index.html`

Y escribid algo de Html, como por ejemplo: 

     `$ <p> Este mi primer párrafo</p>`

Volved a darte permisos: 

     `$ chmod a+rx index.html`

Visitad vuestro espacio CUNIX en el navegador de internet: 

   `$ http://www.columbia.edu/~UNI`

¿Qué veis? :)

Todo esto puede hacerse también con algunos programas como [Filezilla](https://filezilla-project.org/) o [Cyberduck](https://cyberduck.io/?l=en) para trasladar vuestros files al servidor. 


