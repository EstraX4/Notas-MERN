# Comprender la sensibilidad a mayúsculas y minúsculas en variables

En JavaScript, todas las variables y nombres de funciones distinguen entre mayúsculas y minúsculas. Esto significa que las mayúsculas son importantes.

`MYVAR`no es lo mismo que `MyVar`ni `myvar`. Es posible tener varias variables distintas con el mismo nombre pero con mayúsculas y minúsculas diferentes. Se recomienda encarecidamente que, en aras de la claridad, _no_ utilice esta función de idioma.

**Mejores prácticas**

Escribe nombres de variables en JavaScript en camelCase . En camelCase , los nombres de variables de varias palabras tienen la primera palabra en minúsculas y la primera letra de cada palabra subsiguiente está en mayúscula.

**Ejemplos:**

```js
var someVariable;
var anotherVariableName;
var thisVariableNameIsSoLong;
```