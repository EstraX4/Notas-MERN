# Declarar una variable de solo lectura con la palabra clave const

La palabra clave `let`no es la única forma nueva de declarar variables. En ES6, también puede declarar variables usando la `const`palabra clave.

`const`tiene todas las increíbles características que `let`tiene, con la ventaja adicional de que las variables declaradas usando `const`son de solo lectura. Son un valor constante, lo que significa que una vez que se asigna una variable `const`, no se puede reasignar:

```js
const FAV_PET = "Cats";
FAV_PET = "Dogs";

```

La consola mostrará un error debido a la reasignación del valor de `FAV_PET`.

Siempre debe nombrar las variables que no desea reasignar usando la `const`palabra clave. Esto ayuda cuando accidentalmente intenta reasignar una variable que debe permanecer constante.

**Nota:** es común que los desarrolladores usen identificadores de variables en mayúsculas para valores inmutables y minúsculas o camelCase para valores mutables (objetos y matrices). Aprenderá más sobre objetos, matrices y valores inmutables y mutables en desafíos posteriores. También en desafíos posteriores, verá ejemplos de identificadores de variables en mayúsculas, minúsculas o camelCase.