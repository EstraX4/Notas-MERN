# Agregar variables a cadenas

Así como podemos construir una cadena en varias líneas a partir de literales de cadena , también podemos agregar variables a una cadena usando el `+=`operador más igual ( ).

Ejemplo:

```js
const anAdjective = "awesome!";
let ourStr = "freeCodeCamp is ";
ourStr += anAdjective;

```

`ourStr`tendría el valor `freeCodeCamp is awesome!`.