## `Etiqueta de apertura`

La sintaxis de una etiqueta de apertura en HTML es la siguiente:

```html
<nombre-etiqueta atributo="valor">
```

Donde:

- **`<nombre-etiqueta>`** es el nombre de la etiqueta, como **`div`**, **`p`**, **`img`**, **`a`**, etc.
- **`atributo`** es un atributo opcional que se usa para proporcionar información adicional sobre la etiqueta.
- **`valor`** es el valor del atributo.

Por ejemplo, la etiqueta de apertura para un párrafo en HTML se ve así:

```html
<p>
```

Esta etiqueta de apertura define que el contenido que sigue es un párrafo. Si se desea agregar algún atributo, como la clase, la etiqueta de apertura se vería así:

```html
<p class="mi-clase">
```

En este caso, el atributo **`class`** se usa para agregar una clase CSS al párrafo, lo que permite aplicar estilos y reglas de diseño específicas a ese elemento.

## `Etiqueta de cierre`

Una etiqueta de cierre en HTML es el elemento que finaliza una etiqueta y define su alcance. La mayoría de las etiquetas en HTML tienen una etiqueta de apertura y una etiqueta de cierre, que se usan para rodear y definir el contenido que aparece dentro de la etiqueta.

La sintaxis de una etiqueta de cierre en HTML es la siguiente:

```html
</nombre-etiqueta>
```

Donde:

- **`<nombre-etiqueta>`** es el nombre de la etiqueta que se está cerrando, como **`div`**, **`p`**, **`img`**, **`a`**, etc.

Por ejemplo, la etiqueta de cierre para un párrafo en HTML se ve así:

```html
</p>
```

Esta etiqueta de cierre define el final del párrafo y cierra su alcance. Todo el contenido que aparece entre la etiqueta de apertura **`<p>`** y la etiqueta de cierre **`</p>`** se considera contenido del párrafo y se formatea como tal en la página web.

Es importante tener en cuenta que todas las etiquetas de apertura deben tener una etiqueta de cierre correspondiente, de lo contrario, el código HTML no será válido y puede provocar errores en la visualización de la página web.

## `Partes de un documento HTML`

Un documento HTML consta de varias partes que le permiten al navegador interpretar el contenido y presentarlo al usuario de manera adecuada. A continuación se describen las partes principales de un documento HTML:

1. Doctype: Es una declaración especial al inicio del documento que indica al navegador la versión de HTML que se está utilizando en el documento. Por ejemplo, **`<!DOCTYPE html>`** indica que se está utilizando HTML5.
2. Etiqueta html: La etiqueta html envuelve todo el contenido del documento y le indica al navegador que este es un documento HTML.
1. Cabeza (head): La cabeza del documento contiene información que no se muestra directamente en la página web, como el título de la página, los enlaces a hojas de estilo CSS y los scripts de JavaScript.
2. Cuerpo (body): El cuerpo del documento contiene todo el contenido que se mostrará directamente en la página web, como el texto, las imágenes, los videos, los enlaces y otros elementos multimedia.

1. Para agregar un comentario en HTML, coloca el texto que deseas comentar entre los caracteres **`<!--`** y **`->`**.
2. Los comentarios se pueden agregar en cualquier lugar dentro del código HTML, incluyendo entre etiquetas, dentro de atributos y en líneas separadas.
3. Los comentarios en HTML no se muestran en la página web, por lo que se utilizan principalmente para hacer anotaciones sobre el código o desactivar temporalmente secciones de código que no se deseen mostrar.
4. Es importante no abusar de los comentarios y mantenerlos breves y al punto, ya que los comentarios excesivos pueden hacer que el código sea difícil de leer y entender.