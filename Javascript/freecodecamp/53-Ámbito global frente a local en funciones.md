
# Ámbito global frente a local en funciones

Es posible tener variables locales y globales con el mismo nombre. Cuando hace esto, la variable local tiene prioridad sobre la variable global.

En este ejemplo:

```js
const someVar = "Hat";

function myFun() {
  const someVar = "Head";
  return someVar;
}

```

La función `myFun`devolverá la cadena `Head`porque la versión local de la variable está presente.