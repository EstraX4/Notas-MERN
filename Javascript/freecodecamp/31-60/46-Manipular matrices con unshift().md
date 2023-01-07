# Manipular matrices con unshift()

No sólo puede `shift`sacar elementos del principio de una matriz, sino que también puede `unshift`agregar elementos al principio de una matriz, es decir, agregar elementos delante de la matriz.

`.unshift()`funciona exactamente igual que `.push()`, pero en lugar de agregar el elemento al final de la matriz, `unshift()`agrega el elemento al principio de la matriz.

Ejemplo:

```js
const ourArray = ["Stimpson", "J", "cat"];
ourArray.shift();
ourArray.unshift("Happy");
```

Después de `shift`, `ourArray`tendría el valor `["J", "cat"]`. Después de `unshift`, `ourArray`tendría el valor `["Happy", "J", "cat"]`.
