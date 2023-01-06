
# Asignación con un valor devuelto

Si recuerda nuestra discusión sobre [el almacenamiento de valores con el operador de asignación](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/storing-values-with-the-assignment-operator) , todo lo que se encuentra a la derecha del signo igual se resuelve antes de que se asigne el valor. Esto significa que podemos tomar el valor de retorno de una función y asignarlo a una variable.

Supongamos que hemos predefinido una función `sum`que suma dos números, entonces:

```js
ourSum = sum(5, 12);

```

llamará a la `sum`función, que devuelve un valor de `17`y lo asigna a la `ourSum`variable.