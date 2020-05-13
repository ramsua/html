# Formularios en HTML5

## Etiquetas

* `form` - Encierra todos los campos del formulario
* `label` - Representa el nombre del campo
* `input type=`
* `text (default)` - Entrada de texto
  * `password` - Campo para contraseñas (No encripta, solo oculta)
  * `submit` - Botón para enviar el formulario
  * `button` - Igual que submit
  * `image` - Enviar el formulario usando una imágen personalizada
  * `<button></button>` - Por defecto si no se especifica tiene el atributo `type="submit"`
  * `reset` - Reinicia el formulario vaciando los campos
  * `radio` - crea un radio button
  * `checkbox` - crea un checkbox
  * `color` - Permite selecionar un color de una paleta de colores
  * `date` - Permite seleccionar una fecha de un calendario
  * `datetime-local` - Permite seleccionar una fecha y hora
  * `month` - Permite seleccionar un mes de un calendario
  * `week` - Permite seleccionar una semana
  * `email` - Sirve para introducir un email con validación HTML5 (insegura)
  * `file` - Permite subir archivos al servidor
  * `number` - Permite introducir únicamente valores numéricos
  * `range` - Crea un slide para seleccionar un valor numérico
  * `search` - Crea un campo igual que `text` pero con semántica de búsqueda
  * `tel` - Crea un campo para introducir teléfono, en movil sale un teclado diferente
  * `time` - Permite seleccionar una hora
  * `url` - Crea un campo para introducir una url

### `label, input`

  Son elementos inline, aunque por css eso puede cambiar aplicando la propiedad `display: block;` o cualquier valor aceptado en la propiedad `display`.

### `input type="text"`
  
  Un input que no se le especifica el tipo de input que es, ya es un input de tipo texto
