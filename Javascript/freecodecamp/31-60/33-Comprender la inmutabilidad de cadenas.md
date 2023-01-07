# Comprender la inmutabilidad de cadenas

En JavaScript, `String`los valores son inmutables , lo que significa que no se pueden modificar una vez creados.

Por ejemplo, el siguiente código generará un error porque la letra `B`de la cadena `Bob`no se puede cambiar a la letra `J`:

```js
let myStr = "Bob";
myStr[0] = "J";

```

Tenga en cuenta que esto _no_ significa que `myStr`no se pueda reasignar. La única forma de cambiar `myStr`sería asignarle un nuevo valor, así:

```js
let myStr = "Bob";
myStr = "Job";
```
