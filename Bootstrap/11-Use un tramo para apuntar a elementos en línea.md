
# Use un tramo para apuntar a elementos en línea

Puede usar tramos para crear elementos en línea. ¿Recuerdas cuando usamos la `btn-block`clase para hacer que el botón llenara toda la fila?

botón normal

botón de bloqueo btn

Eso ilustra la diferencia entre un elemento "en línea" y un elemento de "bloque".

Al usar el `span`elemento en línea, puede colocar varios elementos en la misma línea e incluso diseñar diferentes partes de la misma línea de manera diferente.

Usando un `span`elemento, anide la palabra `love`dentro del `p`elemento que actualmente tiene el texto `Things cats love`. Luego dale a `span`la clase `text-danger`que ponga el texto en rojo.

Así es como haría esto para el `p`elemento que tiene el texto `Top 3 things cats hate`:

```html
<p>Top 3 things cats <span class="text-danger">hate:</span></p>

```