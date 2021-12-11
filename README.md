# 21724 - Aplicacions Distribuïdes a Internet i Interficies d'Usuari

## [***Práctica HTML***](https://github.com/aNDREUET648/adiu_practica1/blob/master/practica1.html)


## Tabla de contenido
- [Introducción](#introducción).
- [Enunciado](#enunciado).
- [Estructura](#estructura).
- [Consideraciones](#consideraciones).
  - [Sobre la Hoja de estilos](#sobre-la-hoja-de-estilos).
  - [Carácteres especiales](#carácteres-especiales).
  - [Accesibilidad](#accesibilidad).
  - [Validación del código](#validación-del-código).
  - [HTML Responsive Web Design](#HTML-Responsive-Web-Design).
- [Bibliografía y Herramientas](#bibliografía-y-herramientas).

### Introducción

Este archivo `README.md` documenta el desarrollo de esta primera práctica en HTML.

Al tener la necesidad de probar la página en la web para validarla con herramientas online y probarla desde distintos navegadores, decidí abrir cuenta en ***w3c.org*** y utilizar su servicios de _spaces_ donde poder alojarla. La dirección web donde poder visitarla es la siguiente (***https://andreuet.w3spaces.com***).

### Enunciado

  Crea una entrada de blog utilizando HTML, el blog debe contener:

 - Header
 - Author Info
 - Images
 - Hyperlinks
 - Quote (comillas)


##### Sugerencias:

 - Texto personalizado.
 - Añade al blog un formulario de suscripción con campos de entrada de nombre, email y botón de suscripción.
 - Escribe el código teniendo siempre en cuenta la accesibilidad.

##### Control de calidad

  - HTML válido:
    - Etiquetas semánticas HTML5 tales como ```<header>```,```<footer>```, ```<article>```, ```<section>```, etc... se usan para darle sentido al código.
    - Que no haya selectores de secciones o div sin una clase CSS o id.
    - Todo el código en minúsculas.
    - El código no tiene espacios en blanco al final.
    - La _indentación_ (sangrado) es consistente (o todo tabs, o todo 2 spaces, o todo 4 espacios, etc..).
    - El código utiliza una nueva linea para cada bloque, lista o elemento _table_ e indentar cada uno de estos elementos hijos (se acepta poner todos los elementos en una sola línea).
    - Cuando se utilicen valores de atributos de entrecomillados, que el código emplee entrecomillado consistente (```' ' vs "  "```) (simples vs dobles).

  - Reglas de Estilo:
    - HTML documents HTML5 ```<!doctype html>```
    - El código omite los atributos de tipo para las hojas de estilo y los scripts.

  [Enunciado Original](https://github.com/aNDREUET648/adiu_practica1/blob/master/ADIU%20-%20Practice%2029_11_21.pdf)

### Estructura


```
Blog Post
├── index.html                  Página HTML principal
├── hojaestilos.css             Hoja de estilos
└── images                      Directorio de las imágenes
    └── Cardiacsphoto1.jpg       Imagen del grupo Cardiacs
```

### Consideraciones

#### Sobre la Hoja de estilos

  No tanto por el tamaño de la página pero si para empezar a seguir una guía de buenas prácticas y por recomendación de la profesora he decidido insertar mi hoja de estilos de manera externa `External CSS` y no `Internal CSS` como he estado usando hasta ahora, definidos dentro del elemento `<style>`, dentro de la sección '<head>' de la página HTML.

  El archivo ```hojaestilos.css``` no contendrá ningún `tag` HTML, y en la página HTML ```index.html```  se hará referencia a esta hoja de estilos de la siguiente manera:

```
  <head>
    <link rel="stylesheet" href="hojaestilos.css">
  </head>
```

#### Carácteres especiales

Mediante el uso de `<meta charset="UTF-8">` represento la codificación de carácteres UTF-8 (estándar en HTML5) aunque es posible que en algún proceso:

- Otra persona interviene en la creación de la página y emplea codificación 88509-1.
- El servidor web guarda las páginas HTML estáticas.
- El cliente web del usuario no representa igual las páginas....

Para la representación del texto uso una herramienta online para convertir el texto simple a
codificación html (www.textfixeres.com/html/texto-a-html.php)

#### Accesibilidad

Durante la confección de la página se ha tenido todo el tiempo en cuenta el diseño pensando en la accesibilidad. Una vez finalizada, se ha testeado manualmente y validado con distintas herramientas tanto online como extensiones del navegador obteniendo un _Nivel de Conformidad AA_ indicándose así que se han cumplido todos los puntos de control de Prioridad 1 y Prioridad 2 definidos en las Directrices de la **WAI** (_Web Accessibility Initiative_). Incluyendo al final de la página el icono correspondiente a su Nivel de Conformidad.

#### Validación del código

Del mismo modo finalizada la codificación de la página y para comprobar que todo mi código, tanto el HTML como la hoja de estilos CSS eran correctos también han sido evaluados con los validadores de la **W3C** (_The World Wide Web Consortium_) y con un resultado que el archivo ```hojaestilos.css``` es _CSS versión 3 + SVG_ válido! y el archivo ```index.html``` es _Valid XHTML 1.0 Strict_. Es por ello que, al final de la página he incluído los iconos correspondientes.

#### HTML Responsive Web Design

Revisando el tutorial que ofrece w3c.org de HTML [Tutorial HTML](https://www.w3schools.com/html) me fije que tienen un apartado de [HTML Responsive](https://www.w3schools.com/html/html_responsive.asp) con la idea de adaptar la apariencia de las páginas web al dispositivo que se esté utilizando, ya sean móviles, laptops, tablets o desktops. Y aprovechando que era mi primera página web aproveché para incluir simplemente unos `media-query` o `breakpoints`como los llaman para dependiendo de donde se estuviese viendo la página se adaptase en tamaño. Destaqué cuatro tipos, todos los valores los extraje de información del framework `Bootstrap` considerándose como los más comunes.

### Bibliografía y Herramientas

- [W3C](https://www.w3c.org) - Documentación y validadores HTML, CSS, Internacionalización y Accesibilidad
- [w3schools](https://www.w3schools.com/default.asp) - Tutorial HTML, CSS y Responsive Design
- [breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/) - Bootstrap breakpoints
- [Responsive Web Design Tester](https://www.esolutions.se/) - Extensión Chrome
- [WAVE Evaluation Tool](https://webaim.org/) - Extensión Chrome
- [siteimprove](https://siteimprove.com/es-es/) - Extensión Chrome
- [Google Lighthouse](https://developers.google.com/web) - Integrado en Google Chrome
- [Tota11y from Khan Academy](https://khan.github.io/tota11y/) - Extensión Chrome
- [axe DevTools](https://www.deque.com/) - Extensión de las herramientas de desarrollador

---
[aNDREUET648](https://github.com/aNDREUET648)
