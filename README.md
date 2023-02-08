# MF0491_3 PROGRAMACIÓN WEB EN EL ENTORNO CLIENTE
 
- UF1841 ELABORACIÓN DE DOCUMENTOS WEB MEDIANTE LENGUAJES DE MARCAS
- [Guías Bluuweb, HTML Fundamentos](https://bluuweb.dev/01-html/)

## ¿Qué es HTML?

<dl>
    <dt>
        <abbr title="Hipertext Language Markup">HTML</abbr>
    </dt>
    <dd>
    <abbr title="Hipertext Markup Language">HTML</abbr> como indica su acrónimo es un "lenguaje de marcas" (ML) para <em>estructurar</em> (las propias etiquetas son semánticas) el contenido en dichas marcas (en adelante <strong>tags</strong>) 
    </dd>
</dl>

En resumen __HTML__:
- Utiliza __tags__
- Por la característica anterior se le llama (Hipertext) __markup language__
- __Estructura__ contenido

El inventor de <abbr title="Hipertext Markup Language">HTML</abbr> fue __Tim Berners Lee__. Y entre otros logros se encuentran __git__ o el _protocólo_ __http__

## Hola mundo

Ejemplo básico de una __página web__:

```html
<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="utf-8" />
        <title>Mi página de prueba</title>
    </head>
    <body>
        <p>Hola mundo HTML!</p>
    </body>
</html>
```

## HTML format tags

```html
<strong>Texto importante</strong>
<em>Texto enfatizado</em>
<mark>Texto marcado</mark>

<p>
    Este es un párrafo <strong>que contiene texto importante</strong> y además de
    <del>texto eliminado</del>.
</p>

<hr />

<s>Texto tachado</s>
<del>Texto eliminado</del>
<ins>Texto insertado</ins>
<sub>Texto de subíndice</sub>
<sup>Texto en superíndice</sup>
```

## Head tags

```html
<h1>Título principal de nuestro sitio web.</h1>
<h2>Utilízala en los encabezados de secciones.</h2>
<h3>Utilízala en sub-secciones.</h3>
<h4>Utilízala en sub-sub-secciones. o como estimes conveniente</h4>
<h5>Más de lo mismo...</h5>
<h6>No existe el "<h7>" por lo tanto está es la última.</h6>
```

## Divisions tags

```html
<div>Block element.</div>
<span>Inline element.</h2>
```

## Anchor and image tags

```html
<a href="https://youtube.com/bluuweb" target="_blank">Ir a página de Google</a>
```

```html
<img src="https://mdn.mozillademos.org/files/11913/htmlexp.png" alt="alternate text" />
```

## List tags

```html
<!-- Unordered List -->
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    ...
    <li>Elemento N</li>
</ul>

<!-- Ordered List -->
<ol>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
    ...
    <li>Elemento N</li>
</ol>

<!-- Definition List -->
<dl>
    <dt><abbr title="Hipertext Markup Language">HTML</abbr></dt>
    <dd>
        Se trata de un acrónimo es un "lenguaje de marcas" (ML) para <em>estructurar</em> (las propias etiquetas son semánticas) el contenido en dichas marcas
    <dd>
</dl>
```

## Etiquetas semánticas
- [Etiquetas semánticas](https://bluuweb.dev/01-html/#etiquetas-semanticas)

![Etiquetas semánticas](/img/estructura-html5.png)

## Ejercicios de refuerzo

1. A partir de la siguiente captura elaborar el documento HTML correcto

![Primeras tags en HTML](/img/screenshot.png)

- [Enlace al texto](./text.txt)
- [Enlace de etiquetas](https://allthetags.com/)
- Puedes utilizar la herramienta [www.w3chools.com](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_default)

2. Recrear la lista de la imagen

![Ejercicio de listas anidadas](/img/listas.png)

3. Recrear la siguiente captura de pantalla

![Mi página magnífica página web](/img/screenshot2.png)

Consideraciones

- La ruta de la imagen es en remoto y es la siguiente:
https://www.w3.org/html/logo/downloads/HTML5_Badge_512.png

- El botón nos llevará a la siguiente dirección:
https://www.youtube.com/bluuweb

4. Ejercicio. Recrea la siguiente imagen

![Captura](/img/screenshot3.png)


## Sesión 4

## Tablas

- [bluuweb - Nivel intermedio](https://bluuweb.dev/01-html/02-html-intermedio.html)
- [Documentación tablas](./assets/mf0491_3-uf1841_4-html.pdf)

```html
<table border='1'>
    <caption>Titulo de la tabla</caption>
    <!-- Encabezado -->
    <thead>
        <tr>
            <th>Mascota</th>
            <th>Edad</th>
            <th>Color</th>
        </tr>
    </thead>
    <!-- Pie de tabla -->
    <tfoot>
        <tr>
            <th>Mascota</th>
            <th>Edad</th>
            <th>Color</th>
        </tr>
    </tfoot>
    <!-- contenido -->
    <tbody>
        <tr>
            <td>Gato</td>
            <td>3 años</td>
            <td>Negro</td>
        </tr>
        <tr>
            <td>Perro</td>
            <td>1 mes</td>
            <td>Azul</td>
        </tr>
    </tbody>
</table>
```