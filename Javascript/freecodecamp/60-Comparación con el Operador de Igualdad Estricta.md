
# Comparación con el Operador de Igualdad Estricta

La igualdad estricta ( `===`) es la contrapartida del operador de igualdad ( `==`). Sin embargo, a diferencia del operador de igualdad, que intenta convertir ambos valores que se comparan con un tipo común, el operador de igualdad estricta no realiza una conversión de tipo.

Si los valores que se comparan tienen tipos diferentes, se consideran desiguales y el operador de igualdad estricta devolverá falso.

**Ejemplos**

```js
3 ===  3  // true
3 === '3' // false

```

En el segundo ejemplo, `3`es un `Number`tipo y `'3'`es un `String`tipo.