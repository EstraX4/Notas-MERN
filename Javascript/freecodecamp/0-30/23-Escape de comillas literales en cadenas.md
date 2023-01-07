
# Escape de comillas literales en cadenas

Cuando está definiendo una cadena, debe comenzar y terminar con una comilla simple o doble. ¿Qué sucede cuando necesita una cita literal: `"`o `'`dentro de su cadena?

En JavaScript, puede evitar que una comilla se considere como una comilla de fin de cadena colocando una barra invertida ( `\`) delante de la comilla.

```js
const sampleStr = "Alan said, \"Peter is learning JavaScript\".";

```

Esto le indica a JavaScript que la siguiente cita no es el final de la cadena, sino que debería aparecer dentro de la cadena. Entonces, si tuviera que imprimir esto en la consola, obtendría:

```js
Alan said, "Peter is learning JavaScript".
```