
# Use @if y @else para agregar lógica a sus estilos

La `@if`directiva en Sass es útil para probar un caso específico: funciona como la `if`declaración en JavaScript.

```scss
@mixin make-bold($bool) {
  @if $bool == true {
    font-weight: bold;
  }
}

```

Y al igual que en JavaScript, `@else if`y `@else`prueba para más condiciones:

```scss
@mixin text-effect($val) {
  @if $val == danger {
    color: red;
  }
  @else if $val == alert {
    color: yellow;
  }
  @else if $val == success {
    color: green;
  }
  @else {
    color: black;
  }
}
```