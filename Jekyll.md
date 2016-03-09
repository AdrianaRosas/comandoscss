##Instalación Jekyll y Ed 

[Instalar Jekyll](https://jekyllrb.com/docs/installation/) 

Jekyll es un generador de páginas webs. Primero deberemos preparar la versión de una serie de lenguajes. 

Primero debemos installar el [Home Brew](http://brew.sh/):

    `$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
    `$ brew install gnupg gnupg2`
    `$ \curl -sSL https://get.rvm.io | bash -s stable`

El segundo paso es instalar [Ruby Version Managment](https://rvm.io/). Para comprobar qué version tenemos de Ruby:

   `$ ruby --version` <br/>
   `$ ruby 2.2.1p85 (2015-02-26 revision 49769) [x86_64-darwin14]`

Instalar la última version de Ruby, que tomará algún tiempo: 

    `$ rvm install 2.3.0`

A continuación se crea un conjunto de "gems", un fragmento de programa escrito en Ruby que se llamará "MinimalEditions" (aunque lo podéis llamar de otra manera):

    `$ rvm gemset create MinimalEditions
    `$ rvm gemset use MinimalEditions`

A partir de ahora cuando trabajemos con Jekyll deberemos recordar que trabajamos con este grupo de gemas: 

    `$ rvm gemset use MinimalEdition`

Ahora pasamos a instalar Jekyll, podemos seguir las indicaciones del [sito web](https://jekyllrb.com/), que se resumen con estos comandos:  

     `$ gem install jekyll`

Instalaremos también Jekyll scholar para poder gestionar la bibliografía: 

     `$ gem install jekyll-scholar`

Ahora ya tenemos Jekyll. ¡Vamos a crear un website! Nos situamos en una carpeta a elección, creamos una carpeta para un proyecto nuevo 'mkdir nombre`, y entramos dentro `cd nombre`. Y crearemos un sitioweb nuevo: 

     `$ jekyll new nombre_sitio`

Ahora debemos montar el sitio y 

    `$jekyll build`
    `$ jekyll serve`

Vamos a ver aparecer este mensaje: 
    
      `Configuration file: /Users/susannalles/Sites/github.io/susannalles.github.io/9Marzo/Ardillas/_config.yml
       Source: /Users/susannalles/Sites/github.io/susannalles.github.io/9Marzo/Ardillas
       Destination: /Users/susannalles/Sites/github.io/susannalles.github.io/9Marzo/Ardillas/_site
       Incremental build: disabled. Enable with --incremental
       Generating... 
                    done in 0.344 seconds.
       Auto-regeneration: enabled for '/Users/susannalles/Sites/github.io/susannalles.github.io/9Marzo/Ardillas'
       Configuration file: /Users/susannalles/Sites/github.io/susannalles.github.io/9Marzo/Ardillas/_config.yml
       Server address: http://127.0.0.1:4000/
       Server running... press ctrl-c to stop.`

Lo primero que debemos modificar será el `_config.yml` para cambiar el título y las informaciones básicas: `title`, èmail`, `description`,  `baseurl`(la dirección que será pública), `url`(tu página web), `twitter_username`, `github_username`, etc. Y lo salvamos. 
Cancelamos el servidos: Ctrl C`, y activamos el servidor de nuevo: `jekyll serve`. 


###Recursos útiles: 
- [A. Visconti, Building a static website with Jekyll and GitHub Pages, The Programming Historian, March 2016](https://via.hypothes.is/programminghistorian.github.io/ph-submissions/lessons/building-static-sites-with-jekyll-github-pages)
- Links relativos y links absolutos 
- [Temas Jekyll](http://jekyllthemes.org/)