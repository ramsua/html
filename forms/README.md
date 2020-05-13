# Formularios en HTML5

## Etiquetas y atributos

### Etiquetas

| Etiqueta | Descripción |
| ------ | ------ |
| `fieldset` | Se utiliza para agrupar distintos campos los cuales semánticamente pertenecen al mismo grupo. |
| `legend` | Se utiliza para darle un título a los campos agrupados por "fieldset". |
| `label, input` | Son elementos inline, aunque por css eso puede cambiar aplicando la propiedad `display: block;` o cualquier valor aceptado en la propiedad `display`.|
| `datalist` | Crea un filtro interno de la página para buscar. Necesita un input con el atributo `list` que lleva como valor el `id` del `datalist`. |
| `option` | Es donde se almacenan los valores a mostrar en el filtro según lo que busque el usuario. Esta etiqueta debe ser hija de la etiqueta `datalist`. y en el atributo `value` van los valores que se mostrarán según qué busque el usuario. También se utiliza como etiqueta hija en `select`.|
| `select` | Nos permite hacer un desplegable con distintas opciones. |
| `optgroup` | Sirve para agrupar distintas etiquertas `option` que semánticamente pertenecen a un mismo grupo. |
| `textarea` | Una entrada de texto pero enfocada en textos más extensos que un input. |

***

### Atributos

| Atributo | Descripción |
| ------ | ------ |
| `name` | En cualquiera de los campos este atributo se usa para procesar los datos en el servidor. |
| `type` | para espcificar qué tipo de input estamos usando. |
| `boolean` | Un atributo buleano en HTML con que se defina ya se considera "true", y si no define se considera "false" |

***

### Valores de `type`

| Valor | Descripción |
| ------ | ------ |
| `text` | Entrada de texto (Atributo por defecto si no se especifica) |
| `number` | Solamente acepta valores numéricos. |
| `password` | Campo para contraseñas (No encripta, solo oculta) |
| `submit` | Botón para enviar el formulario |
| `button` | Igual que "submit". |
| `image` | Igual que "submit". Hay que añadirle el atributo `src` con la ruta de la imágen. |
| `<button></button>` | Si no se especicfica "type", por defecto es "submit". |
| `reset` | Tanto `<input type="reset"/>` como `<button type="reset"></button>` al presionarse vacían los campos del formulario. |
| `radio` | Mientras pertenezcan al mismo campo, solo podrá tener el "checked" uno solo. Una vez marcado no se puede desmarcar. |
| `checkbox` | Contrario a "radio" perteneciendo al mismo campo, puede haber uno, más de uno o ninguno con el atributo "checked" |
| `date, months y week` | Muestran un calendario según qué tipo de input sea. |
| `time` | Un campo para ingresar la hora. Al igual que con los campos de "date, months y week" cada navegador lo muestra de una forma u otra. |
| `color` | Abre una ventana con una paleta de color donde se puede elegir un color. |
| `email` | Usa validación de HTML 5. Aunque se puede alterar el tipo de input desde el inspector, es necesario que si lo que se va a enviar es un email, el input sea de tipo email. |
| `file` | Sirve para subir al servidor un archivo desde el disco duro. Para este tipo de inputs, el "form" debe tener el atributo `enctype="multipart/form-data"` para para que funcione correctamente. |
| `range` | Es de valor numérico. Sirve para seleccionar una rango, debe establecerse los atributos `min` y `max`.|
| `search` | Parece un input de tipo texto, pero a nivel semántico es distinto. |
| `tel` | Lo mismo que "search". NO valida si es número cuando se envía el formulario. |

***

### Atributos buleanos

| Atributo | Descripción |
| ------ | ------ |
| `required` | Hace que un campo sea obligatorio. |
| `disabled` | Desactiva la interaccion con un campo. |
| `checked` | Marca un "radio" o "checkbox" por defecto. |
| `selected` | Marca un "option" por defecto. |
| `autofocus` | Marca un input por defecto |
| `readonly` | Hace que el campo sea solo de lectura |

***

### Otros atributos

| Atributo | Descripción |
| ------ | ------ |
| `maxlenght minlenght` | Determina la cantidad máxima o mínima de caracteres en un campo |
| `min/max` | Determina el mínimo y máximo en campos numñericos |
| `autocomplete="on"\|"off"` | Se le asigna al formulario. Permite al navegador completar con los datos que tiene almacenados. "on" por defecto. |
| `placeholder`| Establece un valor inicial y se borra al introducir información en ese campo. |
