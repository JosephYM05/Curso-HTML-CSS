# `Encabezados`

Los **encabezados HTML**  o ***heading tags*** son **etiquetas de código HTML**  que se utilizan para definir los títulos y subtítulos de una página. ¿Y cómo se definen estos encabezados? Con la etiqueta __< Hn >__ donde “n” es un número entre 1 y 6 que indica la jerarquía de dicha cabecera.

Es decir, con esta etiqueta podemos implementar seis niveles de encabezado en el documento: __< h1 >__ es el más relevante y __< h6 >__el menos relevante.

## Etiquetas de títulos
El < h1 > es una etiqueta que permite identificar aquellas frases que conforman el título principal de un contenido de una página web. Es fundamental que este encabezado, por ser el más relevante, resuma en una frase el contenido de dicha página. También es esperable que, tanto para los motores de búsqueda como para los usuarios, esté situado en el primer tramo de un documento web.

## Etiqueta de subtítulos

El __< h2 >__ es la etiqueta que en __HTML__ permite identificar a los subtítulos. Normalmente se utilizan para producir un corte en el contenido y por supuesto, brindarle más información a los motores de búsqueda.

## ****Etiquetas**** h3, h4, h5 y h6

Las etiquetas __< h3 >__, __< h4 >__, __< h5 >__ y __< h6 >__ son utilizados para identificar subtítulos de menor jerarquía que se encuentran presentes dentro de secciones de __**< h2 >**__ y permite ser minucioso con el contenido de nuestra página web. Obviamente, a mayor número de etiquetas, menor relevancia para los motores de búsqueda.

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
## ****`¿Cómo utilizar correctamente las etiquetas de encabezado HTML?`****

- Evita omitir niveles de encabezado HTML. Es decir, comienza siempre con __< h1 >__, después utiliza la __< h2 >__ y así sucesivamente.
- Evita utilizar el __< h1 >__ más de una vez en una página. Esta etiqueta se usa una vez para mostrar el título de la página, seguido por los demás encabezados HTML, que comienzan con __< h2 >__.
- Tampoco debes utilizar niveles inferiores para reducir el tamaño de la fuente. Para esto, aplica la propiedad **CSS font-size** ;)

### **`¿Para qué se usa la etiqueta “H1”?`**

El __< h1 >__ es una etiqueta que permite identificar aquellas frases que conforman el título principal de un contenido de una página web. Es fundamental que este encabezado, por ser el más relevante, resuma en una frase el contenido de dicha página.

### **`¿Para qué se utiliza la etiqueta “H2”?`**

El __< h2 >__ es la etiqueta que en HTML permite identificar a los subtítulos. Normalmente se utilizan para producir un corte en el contenido y por supuesto, brindarle más información a los motores de búsqueda.

### **`¿Cuál es la función de las etiquetas "H3", "H4", "H5" y "H6"?`**

Las etiquetas __< h3 >__, __< h4 >__, __< h5 >__ y __< h6 >__ son utilizados para identificar subtítulos de menor jerarquía que se encuentran presentes dentro de secciones de __< h2 >__ y permite ser minucioso con el contenido de nuestra página web. Obviamente, a mayor número de etiquetas, menor relevancia para los motores de búsqueda.

### **`¿Cómo utilizar correctamente las etiquetas de encabezado HTML?`**

Para utilizar correctamente las etiquetas de encabezado HTML sigue alguna de estas prácticas: evita omitir niveles de encabezado HTML, evita utilizar el __< h1 >__ más de una vez en una página. Tampoco debes utilizar niveles inferiores para reducir el tamaño de la fuente, para esto, aplica la propiedad CSS font-size.

> `Referencias:`  [¿Qué son los encabezados en HTML? | Henry Blog (soyhenry.com)](https://blog.soyhenry.com/que-son-los-encabezados-en-html/#:~:text=Los%20encabezados%20HTML%20o%20heading,la%20jerarqu%C3%ADa%20de%20dicha%20cabecera.)
>
