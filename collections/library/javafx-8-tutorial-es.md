---
layout: article
title: "JavaFX 8 Tutorial"
date: 2014-09-10 00:00
updated: 2014-09-10 00:00
slug: javafx-8-tutorial/es
canonical: /java/javafx-8-tutorial-intro/
github: https://github.com/marcojakob/code.makery.ch/edit/master/collections/library/javafx-8-tutorial-es.md
description: "Este tutorial en siete partes  describe el dise�o, programaci�n y publicaci�n de una aplicaci�n de contactos con JavaFX."
image: /assets/library/javafx-8-tutorial/addressapp.png
published: true
prettify: true
comments: false
sidebars:
- header: "Art�culos en esta serie"
  body:
  - text: "Introducci�n"
    link: /library/javafx-8-tutorial/es/
    paging: Intro
    active: true
  - text: "Parte 1: Scene Builder"
    link: /library/javafx-8-tutorial/es/part1/
    paging: 1
  - text: "Parte 2: Model y TableView"
    link: /library/javafx-8-tutorial/es/part2/
    paging: 2
  - text: "Parte 3: Interaccionando con el usuario usuario"
    link: /library/javafx-8-tutorial/es/part3/
    paging: 3
  - text: "Parte 4: Hojas de estilo CSS"
    link: /library/javafx-8-tutorial/es/part4/
    paging: 4
  - text: "Parte 5: Persistencia de datos con XML"
    link: /library/javafx-8-tutorial/es/part5/
    paging: 5
  - text: "Parte 6: Gr�ficos para estad�sticas"
    link: /library/javafx-8-tutorial/es/part6/
    paging: 6
  - text: "Parte 7: Publicaci�n con e(fx)clipse"
    link: /library/javafx-8-tutorial/es/part7/
    paging: 7
- header: Linguagens
  body:
  - text: English
    link: /java/javafx-8-tutorial-intro/
    icon-css: fa fa-fw fa-globe
  - text: Espa�ol
    link: /library/javafx-8-tutorial/es/
    icon-css: fa fa-fw fa-globe
    active: true
---

<div class="alert alert-warning">
  <i class="fa fa-language"></i> This page is beeing translated to Spanish. If you'd like to help out please read <a href="/library/how-to-contribute/" class="alert-link">how to contribute</a>.
</div>

JavaFX proporciona a los desarrolladores de Java una nueva plataforma gr�fica.  JavaFX 2.0 se public� en octubre del 2011 con la intenci�n de reemplazar a Swing en la creaci�n de nuevos interfaces gr�ficos de usario (IGU). Cuando empec� a ense�ar JavaFX en 2011 era una tecnolog�a muy incipiente todav�a. No hab�a libros sobre JavaFX que fueran **adecuados para estudiantes de programaci�n noveles**, as� es que empec� a escribir una serie de tutoriales muy detallados sobre JavaFX.

![JavaFX Logo](/assets/java/javafx-2-tutorial-intro/javafx-logo.png)

El tutorial te gu�a a lo largo del dise�o, programaci�n y publicaci�n de una aplicaci�n de contactos (libreta de direcciones) mediante JavaFX. Este es el aspecto que tendr� la aplicaci�n final:

![Screenshot AddressApp Part 1](/assets/java/javafx-2-tutorial-intro/addressapp01.png)


## Lo que aprender�s

* Creando un nuevo projecto JavaFX
* Usando Scene Builder para dise�ar la interfaz de usuario
* Estructurando una aplicaci�n con el patr�n Modelo Vista Controlador (MVC)
* Uso de `ObservableLists` para la actualizaci�n autom�tica de la interfaz de usuario
* Uso de `TableView` y respuesta a cambios de selecci�n en la table
* Creaci�n de un di�logo personalizado para editar personas
* Validando la entrada del usuario
* Aplicando estilos mediante CSS
* Persistencia de datos mediante XML
* Guardando el �ltimo archivo abierto en las preferencias del usuario
* Crenado un gr�fico JavaFX para mostrar estad�sticos
* Publicaci�n de una aplicaci�n JavaFX nativa

Despu�s de completar esta serie de tutoriales deber�as estar preparado para construir aplicaciones sofisticadas con JavaFX.

## Como usar este tutorial

Hay dos formas de utilizarlo

* **m�ximo-aprendizaje*** Creando tu propio proyecto JavaFX desde cero.
* **m�xima-r�pidez** Importa el c�digo fuente de una parte del tutorial en tu entorno de desarrollo (es un proyecto Eclipse, pero puedes usar otros entornos, como Netbeans, con ligeras modificaciones). Despu�s revisa el tutorial para entender el c�digo. Este enfoque tambi�n resulta �til si te quedas atascado en la creaci�n de tu propio c�digo.


� Espero que te diviertas y aprendas mucho ! Empieza en  [Part 1: Scene Builder](/java/javafx-2-tutorial-es-part1/).