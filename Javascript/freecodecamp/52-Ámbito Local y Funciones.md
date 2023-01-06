
# Ámbito Local y Funciones

Las variables que se declaran dentro de una función, así como los parámetros de la función, tienen alcance local . Eso significa que solo son visibles dentro de esa función.

Aquí hay una función `myTest`con una variable local llamada `loc`.

```js
function myTest() {
  const loc = "foo";
  console.log(loc);
}

myTest();
console.log(loc);

```

La `myTest()`llamada a la función mostrará la cadena `foo`en la consola. La `console.log(loc)`línea (fuera de la `myTest`función) arrojará un error, ya `loc`que no está definida fuera de la función.