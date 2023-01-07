# Manipular matrices con shift ()

`pop()`siempre elimina el último elemento de una matriz. ¿Qué sucede si desea eliminar el primero?

Ahí es donde `.shift()`entra en juego. Funciona igual que `.pop()`, excepto que elimina el primer elemento en lugar del último.

Ejemplo:

```js
const ourArray = ["Stimpson", "J", ["cat"]];
const removedFromOurArray = ourArray.shift();
```

`removedFromOurArray`tendría un valor de la cadena `Stimpson`y `ourArray`tendría `["J", ["cat"]]`.
