# Formularios en HTML5

## Etiquetas y atributos

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

***

### Etiquetas

| Etiqueta | Descripción |
| ------ | ------ |
| `label, input` | Son elementos inline, aunque por css eso puede cambiar aplicando la propiedad `display: block;` o cualquier valor aceptado en la propiedad `display`.|

### Atributos

| Atributo | Descripción |

| ------ | ------ |

| `text` | Un input que no se le especifica el tipo de input que es, ya es un input de tipo texto. |

| `number` | Solamente acepta valores numéricos. |

| `password` | No encripta el texto introducido, solo lo oculta cambiándolo por asteríscos. |

| `submit` | Envia el formulario, deja vacío los campos del formulario y recarga la página. |

| `button` | Igual que `submit`. |

| `image` | Igual que `submit`. Hay que añadirle el atributo `src` con la ruta de la imágen. |

| `<button></button>` | Si no se especicfica `type`, por defecto es `submit`. |

| `reset` | Tanto `<input type="reset"/>` como `<button type="reset"></button>` al presionarse vacían los campos del formulario. |

| `radio` | Mientras pertenezcan al mismo campo, solo podrá tener el `checked` uno solo. Una vez marcado no se puede desmarcar. |

| `checkbox` | Contrario a `radio` perteneciendo al mismo campo, puede haber uno, más de uno o ninguno con el atributo `checked` |

| `date, months y week` | Muestran un calendario según qué tipo de input sea. |

| `time` | Un campo para ingresar la hora. Al igual que con los campos de "date, months y week" cada navegador lo muestra de una forma u otra. |

| `color` | Abre una ventana con una paleta de color donde se puede elegir un color. |

| `email` | Usa validación de HTML 5. Aunque se puede alterar el tipo de input desde el inspector, es necesario que si lo que se va a enviar es un email, el input sea de tipo email. |

| `file` | Sirve para subir al servidor un archivo desde el disco duro. Para este tipo de inputs, el `form` debe tener el atributo `enctype="multipart/form-data" para para que funcione correctamente`. |
| `range` | Es de valor numérico. Sirve para seleccionar una rango, debe establecerse los atributos `min` y `max`.|
