# 21724 - Aplicacions Distribuïdes a Internet i Interficies d'Usuari

## ***Práctica HTML***


## Tabla de contenido
- [Introducción](#introducción).
- [Enunciado](#enunciado).
- [Estructura](#estructura).
- [Consideraciones](#consideraciones).
  - [Sobre la Hoja de estilos](#hoja-de-estilos).
  - [Carácteres especiales](#caracteres-especiales).
  - [Accesibilidad](#accesibilidad).
  - [Validación del código](#validacion-del-codigo).
- [Bibliografía y Herramientas](#bibliografia-y-herramientas)

### Introducción

Este archivo `README.md` documenta el desarrollo de esta primera práctica en HTML.

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

#### Validación del código

### Bibliografia y Herramientas


---
[aNDREUET648](https://github.com/aNDREUET648)
