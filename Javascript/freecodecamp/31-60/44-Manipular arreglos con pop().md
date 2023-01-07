
# Manipular arreglos con pop()

Otra forma de cambiar los datos en una matriz es con la `.pop()`función.

`.pop()`se utiliza para extraer un valor del final de una matriz. Podemos almacenar este valor extraído asignándolo a una variable. En otras palabras, `.pop()`elimina el último elemento de una matriz y devuelve ese elemento.

Cualquier tipo de entrada se puede extraer de una matriz: números, cadenas, incluso matrices anidadas.

```js
const threeArr = [1, 4, 6];
const oneDown = threeArr.pop();
console.log(oneDown);
console.log(threeArr);

```

El primero `console.log`mostrará el valor `6`y el segundo mostrará el valor `[1, 4]`.