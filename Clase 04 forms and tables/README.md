# 4. Formularios

Los formularios son los elementos en los que se integran los botones y las áreas de texto que se utilizan para que los usuarios introduzcan sus datos o que puedan elegir entre varias opciones. Veamos las etiquetas que se utilizan para la **creación de formularios en HTML**.

# 4.1. Etiquetas para la creación de formularios

El principio y final de un formulario se define con las etiquetas < form> y </>. Dentro de las etiquetas de apertura y cierre de form se pueden incluir diferentes elementos que son enviados para ser procesados por el servidor web. HTML5 dispone de un gran número de elementos de formulario como puedes ver en la siguiente tabla.

| Elemento | Descripción |
| --- | --- |
| < form> | Define un formulario. |
| < fieldset> | Permite organizar en grupos los campos de un formulario. |
| < legend> | Representa el título de un < fieldset>. |
| < label> | Representa el título de un elemento de control de un formulario. |
| < input> | Se usa para crear controles interactivos que reciben datos del usuario. https://developer.mozilla.org/es/docs/Web/HTML/Elemento/input |
| < button> | Representa un botón. |
|  |  |


| < option> | Representa una opción en un elemento < select> o < datalist>. |
| --- | --- |
| < select> | Representa un elemento de control que permite la selección entre un conjunto de opciones < option>. |
| < optgroup> | Representa un conjunto de opciones, agrupadas lógicamente. |
| < datalist> | Representa un elemento de control que permite la selección entre un conjunto de opciones < option>. |
| < textarea> | Representa un elemento de control de edición de texto multilínea. |
| < output> | Representa el resultado de un cálculo. |


### Ejemplo:
Ejemplo completo: [https://github.com/JosephYM07/Curso-HTM-CSS/blob/0076a8dc984aad7107595b91820624f533095f8f/Clase%2004%20forms%20and%20tables/1-forms.html]



**Explicación:**

```html
<label for="Nombre de usuario">Nombre de usuario</label>
        <input name="nombreusuario" id="nombreusuario" />
```

```html
<label for="password">Contraseña</label>
        <input name="password" id="password" />
```

La etiqueta **`< label>`** y un elemento **`< input>`** en HTML. La etiqueta **`<label>`** se utiliza para agregar una descripción o etiqueta a un elemento de formulario HTML, en este caso, al campo de entrada de texto definido por la etiqueta **`<input>`**.

El atributo **`for`** de la etiqueta **`<label>`** se utiliza para indicar qué elemento de formulario está etiquetando. En este caso, el valor del atributo **`for`** coincide con el valor del atributo **`id`** del elemento **`<input>`**. Esto significa que cuando el usuario hace clic en la etiqueta **`<label>`**, el cursor se activa en el campo de entrada de texto asociado.

```html
<label for="comentarios">Comentarios</label>
        <textarea name="comentarios" id="comentarios"></textarea>
```

Por su parte, el elemento **`<textarea>`**es similar a un campo de entrada de texto **`<input>`**, pero está diseñado para recopilar una cantidad significativa de texto. Al igual que la etiqueta **`<input>`** , la etiqueta **`<textarea>`** tiene el atributo **`name`**, que especifica el nombre del campo de entrada que se utilizará para enviar los datos del formulario al servidor. También tiene el atributo **`id`**, que especifica un identificador único para el elemento, que se usa en conjunto con la etiqueta **`<label>`** para mejorar la accesibilidad y la usabilidad del formulario.

En resumen, estas etiquetas **`<label>`** se utilizan para proporcionar una descripción descriptiva de los campos de entrada de texto y el área de texto, lo que ayuda a los usuarios a entender el propósito de estos campos y lo que se espera que ingresen allí tanto ************USUARIO, CONTRASEÑA Y COMENTARIOS************.