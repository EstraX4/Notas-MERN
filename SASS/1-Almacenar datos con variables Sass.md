
# Almacenar datos con variables Sass

Una característica de Sass que es diferente a CSS es que usa variables. Se declaran y configuran para almacenar datos, de forma similar a JavaScript.

En JavaScript, las variables se definen usando las palabras clave `let`y `const`. En Sass, las variables comienzan con un `$`seguido del nombre de la variable.

Aqui hay un par de ejemplos:

```scss
$main-fonts: Arial, sans-serif;
$headings-color: green;

```

Y para usar las variables:

```scss
h1 {
  font-family: $main-fonts;
  color: $headings-color;
}

```

Un ejemplo en el que las variables son útiles es cuando varios elementos deben tener el mismo color. Si se cambia ese color, el único lugar para editar el código es el valor de la variable.