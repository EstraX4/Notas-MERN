# Explore las diferencias entre las palabras clave var y let

Uno de los mayores problemas con la declaración de variables con la `var`palabra clave es que puede sobrescribir fácilmente las declaraciones de variables:

```js
var camper = "James";
var camper = "David";
console.log(camper);

```

En el código anterior, la `camper`variable se declara originalmente como `James`, y luego se anula para que sea `David`. A continuación, la consola muestra la cadena `David`.

En una aplicación pequeña, es posible que no se encuentre con este tipo de problema. Pero a medida que su base de código se vuelve más grande, puede sobrescribir accidentalmente una variable que no tenía la intención de sobrescribir. Debido a que este comportamiento no arroja un error, la búsqueda y corrección de errores se vuelve más difícil.

Se introdujo una palabra clave llamada `let`en ES6, una actualización importante de JavaScript, para resolver este posible problema con la `var`palabra clave. Aprenderá sobre otras características de ES6 en desafíos posteriores.

Si reemplaza `var`con `let`en el código anterior, se produce un error:

```js
let camper = "James";
let camper = "David";

```

El error se puede ver en la consola de su navegador.

Entonces, a diferencia `var`de , cuando usa `let`, una variable con el mismo nombre solo se puede declarar una vez.