# Use @for para crear un bucle Sass

La `@for`directiva agrega estilos en un bucle, muy similar a un `for`bucle en JavaScript.

`@for`se utiliza de dos maneras: "de principio a fin" o "de principio a fin". La principal diferencia es que "de principio **a** fin" _excluye_ el número final como parte del conteo, y "de principio **a** fin" _incluye_ el número final como parte del conteo.

Aquí hay un ejemplo de principio **a** fin:

```scss
@for $i from 1 through 12 {
  .col-#{$i} {
    width: 100%/12 * $i;
  }
}
```

La `#{$i}`parte es la sintaxis para combinar una variable ( `i`) con texto para formar una cadena. Cuando el archivo Sass se convierte a CSS, se ve así:

```scss
.col-1 {
  width: 8.33333%;
}

.col-2 {
  width: 16.66667%;
}

... .col-12 {
  width: 100%;
}
```

Esta es una forma poderosa de crear un diseño de cuadrícula. Ahora tiene doce opciones para anchos de columna disponibles como clases CSS.
