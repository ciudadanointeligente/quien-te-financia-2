#QUIEN TE FINANCIA

Este sitio fue desarrollado usando [GitHub Pages](http://pages.github.com) y [Jekyll](https://github.com/mojombo/jekyll).
Basado en eltheme [Left](http://cl.ly/image/3S2r1p2C0E2B/content) de Zach Holman. 

La documentación está incompleta, pero siéntanse libres de contactarnos en info@ciudadanointeligente.org 

## Instalación

- Install Jekyll: `gem install jekyll`
- [Forkear este repo](https://github.com/ciudadanointeligente/quien-te-financia-2/tree/basic-qtf)
- Clonarlo: `git clone https://github.com/YOUR-USER/quien-te-financia-2`
- Run the jekyll server: `jekyll --server`


Usar la versión de la rama "basic-qtf".


## Personalizarlo

Lo siguiente es cambiar la información base del archivo: _config.yml

De ahí sacaremos el nombre de la organización, el nombre de usuario de Twitter, hashtag de la campaña para incluir en los twitts, etc.


Algunas otras cosas que cambiar:

- archivo CNAME: 
	Si vas a usar Github pages debes incluir acá el dominio que vas a usar.
	En este archivo sólo debe ir una url en la primera linea y nada más  (así: `example.com`).

- favicon.ico

- apple-touch-icon.png



##Agregar contenido

###Crear un candidato:###
Crear un post y asignarle un **layout: candidato** . 
No olvidar asignarle una categoría para que aparezca en el home: 'whitelist' si ha respondido, 'blacklist' si no ha respondido. 

###Completar la información del candidato ###
El post '2013-00-00-candidato_muestra.markdown' incluye comentarios explicando cada uno de los campos a llenar.



## Deployment

Recomendamos deployar con[GitHub Pages](http://pages.github.com)- es lo más fácil.


