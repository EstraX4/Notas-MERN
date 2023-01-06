
# Comprender el valor indefinido devuelto por una función

Una función puede incluir la `return`declaración pero no tiene que hacerlo. En el caso de que la función no tenga una `return`declaración, cuando la llama, la función procesa el código interno pero el valor devuelto es `undefined`.

**Ejemplo**

```js
let sum = 0;

function addSum(num) {
  sum = sum + num;
}

addSum(3);

```

`addSum`es una función sin `return`sentencia. La función cambiará la `sum`variable global pero el valor devuelto de la función es `undefined`.