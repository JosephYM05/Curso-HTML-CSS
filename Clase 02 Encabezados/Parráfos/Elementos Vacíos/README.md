# `Encabezados`

Los **encabezados HTML**  o ***heading tags*** son **etiquetas de código HTML**  que se utilizan para definir los títulos y subtítulos de una página. ¿Y cómo se definen estos encabezados? Con la etiqueta <Hn> donde “n” es un número entre 1 y 6 que indica la jerarquía de dicha cabecera.

Es decir, con esta etiqueta podemos implementar seis niveles de encabezado en el documento: **<h1>** es el más relevante y **<h6>** el menos relevante.

## ******************Etiquetas de títulos******************
El **<h1>** es una etiqueta que permite identificar aquellas frases que conforman el título principal de un contenido de una página web. Es fundamental que este encabezado, por ser el más relevante, resuma en una frase el contenido de dicha página. También es esperable que, tanto para los motores de búsqueda como para los usuarios, esté situado en el primer tramo de un documento web.

## ********************Etiqueta de subtítulos********************
El **<h2>** es la etiqueta que en **HTML** permite identificar a los subtítulos. Normalmente se utilizan para producir un corte en el contenido y por supuesto, brindarle más información a los motores de búsqueda.

## ****Etiquetas**** h3, h4, h5 y h6
Las etiquetas **<h3>, <h4>, <h5> y <h6>** son utilizados para identificar subtítulos de menor jerarquía que se encuentran presentes dentro de secciones de **<h2>** y permite ser minucioso con el contenido de nuestra página web. Obviamente, a mayor número de etiquetas, menor relevancia para los motores de búsqueda.

```html
<html>
  <head>
    <meta charset="utf--8" />
    <title>Encabezados</title>
  </head>
  <body>
    <!--Texto sin formato - texto por defecto 16 pixeles -->
    Este es un texto antes del título
    <h1>Encabezado 1</h1>
    <h2>Encabezado 2</h2>
    <h3>Encabezado 3</h3>
    <h4>Encabezado 4</h4>
    <h5>Encabezado 5</h5>
    <h6>Encabezado 6</h6>
  </body>
</html>
```
