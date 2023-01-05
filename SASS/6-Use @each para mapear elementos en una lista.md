
# Use @each para mapear elementos en una lista

El último desafío mostró cómo la `@for`directiva usa un valor inicial y final para realizar un bucle una cierta cantidad de veces. Sass también ofrece la `@each`directiva que recorre cada elemento en una lista o mapa. En cada iteración, la variable se asigna al valor actual de la lista o el mapa.

```scss
@each $color in blue, red, green {
  .#{$color}-text {color: $color;}
}

```

Un mapa tiene una sintaxis ligeramente diferente. Aquí hay un ejemplo:

```scss
$colors: (color1: blue, color2: red, color3: green);

@each $key, $color in $colors {
  .#{$color}-text {color: $color;}
}

```

Tenga en cuenta que la `$key`variable es necesaria para hacer referencia a las claves en el mapa. De lo contrario, el CSS compilado tendría `color1`, `color2`... en él. Los dos ejemplos de código anteriores se convierten en el siguiente CSS:

```scss
.blue-text {
  color: blue;
}

.red-text {
  color: red;
}

.green-text {
  color: green;
}
```