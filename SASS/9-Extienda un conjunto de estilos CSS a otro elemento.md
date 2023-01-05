# Extienda un conjunto de estilos CSS a otro elemento

Sass tiene una característica llamada `extend`que facilita tomar prestadas las reglas CSS de un elemento y construir sobre ellas en otro.

Por ejemplo, el siguiente bloque de reglas CSS le da estilo a una `.panel`clase. Tiene un `background-color`, `height`y `border`.

```scss
.panel {
  background-color: red;
  height: 70px;
  border: 2px solid green;
}
```

Ahora quiere otro panel llamado `.big-panel`. Tiene las mismas propiedades base que `.panel`, pero también necesita un `width`y `font-size`. Es posible copiar y pegar las reglas CSS iniciales desde `.panel`, pero el código se vuelve repetitivo a medida que agrega más tipos de paneles. La `extend`directiva es una forma sencilla de reutilizar las reglas escritas para un elemento y luego agregar más para otro:

```scss
.big-panel {
  @extend .panel;
  width: 150px;
  font-size: 2em;
}
```

`.big-panel`Tendrán las mismas propiedades que además `.panel`de los nuevos estilos.
