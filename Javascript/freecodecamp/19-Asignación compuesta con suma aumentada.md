
# Asignación compuesta con suma aumentada

En programación, es común usar asignaciones para modificar el contenido de una variable. Recuerde que todo lo que está a la derecha del signo igual se evalúa primero, por lo que podemos decir:

```js
myVar = myVar + 5;

```

para agregar `5`a `myVar`Dado que este es un patrón tan común, hay operadores que realizan tanto una operación matemática como una asignación en un solo paso.

Uno de esos operadores es el `+=`operador.

```js
let myVar = 1;
myVar += 5;
console.log(myVar);

```

`6`se mostraría en la consola.