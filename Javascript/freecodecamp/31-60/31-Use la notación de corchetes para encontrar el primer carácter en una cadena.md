# Use la notación de corchetes para encontrar el primer carácter en una cadena

La notación de corchetes es una forma de obtener un carácter en un índice específico dentro de una cadena.

La mayoría de los lenguajes de programación modernos, como JavaScript, no comienzan a contar desde 1 como lo hacen los humanos. Comienzan en 0. Esto se conoce como indexación basada en cero .

Por ejemplo, el carácter en el índice 0 de la palabra `Charles`es `C`. Entonces `const firstName = "Charles"`, si puede obtener el valor de la primera letra de la cadena usando `firstName[0]`.

Ejemplo:

```js
const firstName = "Charles";
const firstLetter = firstName[0];

```

`firstLetter`tendría un valor de la cadena `C`.