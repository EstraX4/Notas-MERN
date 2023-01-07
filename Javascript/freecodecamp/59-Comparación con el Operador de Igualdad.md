# Comparación con el Operador de Igualdad

Hay muchos operadores de comparación en JavaScript. Todos estos operadores devuelven un valor booleano `true`o `false`.

El operador más básico es el operador de igualdad `==`. El operador de igualdad compara dos valores y devuelve `true`si son equivalentes o `false`no. Tenga en cuenta que la igualdad es diferente de la asignación ( `=`), que asigna el valor a la derecha del operador a una variable a la izquierda.

```js
function equalityTest(myVal) {
  if (myVal == 10) {
    return "Equal";
  }
  return "Not Equal";
}

```

Si `myVal`es igual a `10`, el operador de igualdad devuelve `true`, por lo que el código entre llaves se ejecutará y la función devolverá `Equal`. De lo contrario, la función devolverá `Not Equal`. Para que JavaScript compare dos tipos de datos diferentes (por ejemplo, `numbers`y `strings`), debe convertir un tipo en otro. Esto se conoce como tipo de coerción. Sin embargo, una vez que lo hace, puede comparar términos de la siguiente manera:

```js
1   ==  1  // true
1   ==  2  // false
1   == '1' // true
"3" ==  3  // true
```