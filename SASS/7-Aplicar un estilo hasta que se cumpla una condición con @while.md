
# Aplicar un estilo hasta que se cumpla una condición con @while

La `@while`directiva es una opción con una funcionalidad similar al `while`bucle de JavaScript. Crea reglas CSS hasta que se cumple una condición.

El `@for`desafío dio un ejemplo para crear un sistema de cuadrícula simple. Esto también puede funcionar con `@while`.

```scss
$x: 1;
@while $x < 13 {
  .col-#{$x} { width: 100%/12 * $x;}
  $x: $x + 1;
}

```

Primero, defina una variable `$x`y configúrela en 1. Luego, use la `@while`directiva para crear el sistema de cuadrícula _while_  `$x` es menor que 13. Después de configurar la regla CSS para `width`, `$x`se incrementa en 1 para evitar un bucle infinito.