<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Plantilla Irontec para presentaciones](#plantilla-irontec-para-presentaciones)
	- [Pasos para crear tu proyecto](#pasos-para-crear-tu-proyecto)
		- [Partiendo de este repositorio](#partiendo-de-este-repositorio)
		- [Desde cero](#desde-cero)
	- [Plugins extra utilizados](#plugins-extra-utilizados)
	- [Modo de uso](#modo-de-uso)
		- [Trucos](#trucos)
			- [Imprimir](#imprimir)
		- [Notas](#notas)
		- [Resaltado de sintaxis](#resaltado-de-sintaxis)

<!-- /TOC -->

# Plantilla Irontec para presentaciones
Este repositorio pretende ser una plantilla para las transparencias corporativas

Vas a necesitar, como dependencias, al menos los siguientes paquetes:
* [npm](https://www.npmjs.com/)
* [bower](https://bower.io/)
* [grunt](https://gruntjs.com/)
* [yeoman](http://yeoman.io/)


## Pasos para crear tu proyecto
Aquí hay dos formas:
* Partiendo de este repositorio
* Desde cero, tirando de paquetes

### Partiendo de este repositorio
Básicamente lo que tienes que hacer es hacer un clone de este repositorio. Necesitarás las dependencias arriba expuestas.

Los comandos a ejecutar una vez hecho el clone:

```
npm install

bower install

grunt serve
```

Tendrás que modificar el fichero **slides/list.json ** y crear tus propias transparencias dentro del directorio **slides**.

También deberías modificar los ficheros
* **templates/_index.html**: Cambiar el **title** de la presentación
* **bower.json**: cambiar el nombre y la versión de la presentación
* **package.json**: cambiar el nombre y la versión de la presentación

### Desde cero
Los pasos dados para crear este repositorio son los siguientes. Puedes hacer lo mismo para tu proyecto.

* Crear la plantilla para reveal:

```
yo reveal
```

Nos realizará unas preguntas:
* What are you going to talk about? **Irontec**
* What version should we put in the package.json file? **1.0.0**
* Do you want to use Sass to create a custom theme? **n**
* What Reveal.js theme would you like to use? **black**
* Do you want to deploy your presentation to Github Pages? **n**

Las respuestas que se han dado durante la creación de esta plantilla son las puestas después de las preguntas en negrita. Deberías responder como tu quieras.

Para iniciar el servidor:

```
grunt serve
```

Con esto ya tienes la plantilla base para poder empezar a crear las transparencias, pero ten en cuenta que para este repositorio hemos utilizado plugins extra. Mira el siguiente punto

## Plugins extra utilizados
Para la creación de este repositorio hemos utilizado los siguientes plugins extra:
* [reveal-irontec-theme](https://github.com/irontec/reveal-irontec-theme)
* [reveal.js-menu](https://github.com/denehyg/reveal.js-menu)


## Modo de uso
Básicamente lo que hay que hacer es generar las transparencias dentro del directorio **slides** y añadirlas en el orden que se quiera en el fichero **slides/list.json**. No hay que olvidar tener el servidor inicializado:

```
grunt serve
```

Esto lo que hará será modificar el fichero **index.html** generándolo desde el directorio templates y teniendo en cuenta las transparencias creadas e indicadas en el fichero **slides/list.json**.


### Subir a github
Si queremos subirlo a Github o en nuestro GitLab y queremos que funcione en modo estático, tendrás que commitear el directorio **bower_components**. Para ello tendrás que modificar el fichero **.gitignore**.

### Trucos
Existen varios atajos de teclado que nos facilitan las cosas:
* **esc**: nos muestra todas las transparencias
* **?**: nos muestra estos atajos de teclado
* **s**: nos abre una nueva ventana con la transparencia actual, la siguiente, las notas y un reloj
* **m**: como hemos añadido el plugin de menú, nos abre el menú

#### Imprimir
Para poder imprimir las transparencias tendremos que añadir **?print-pdf** en la URL.

### Notas
A cada transparencia puedes poner notas que sólo veras si pulsas **s**. Esto abrirá una nueva ventana donde podrás ver la transparencia actual, la siguiente y las notas de la transparencia actual.

Para crear una nota en la transparencias tendrás que poner lo siguiente en la transparencia (puedes ver un ejemplo en **slides/slide-title.md**)

    note:
        Put your speaker notes here.
        You can see them pressing 's'.

### Resaltado de sintaxis
Para el resaltado de sintaxis se hace uso de la librería [highlightjs](https://highlightjs.org/). En la plantilla se hace uso del tema **atom-one-dark**.

## TO-DO
Debemos modificar el theme de Irontec para tener en cuenta el menú, mejorarlo en generar y tener en cuenta cuando se imprime las transparencias.
