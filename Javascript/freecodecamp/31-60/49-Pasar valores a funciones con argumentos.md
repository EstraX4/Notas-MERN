
# Pasar valores a funciones con argumentos

Los parámetros son variables que actúan como marcadores de posición para los valores que se deben ingresar a una función cuando se la llama. Cuando se define una función, normalmente se define junto con uno o más parámetros. Los valores reales que se ingresan (o "pasan" ) en una función cuando se llama se conocen como argumentos .

Aquí hay una función con dos parámetros, `param1`y `param2`:

```js
function testFun(param1, param2) {
  console.log(param1, param2);
}

```

Entonces podemos llamar `testFun`así: `testFun("Hello", "World");`. Hemos pasado dos argumentos de cadena, `Hello`y `World`. Dentro de la función, `param1`será igual a la cadena `Hello`y `param2`será igual a la cadena `World`. Tenga en cuenta que podría `testFun`volver a llamar con diferentes argumentos y los parámetros tomarían el valor de los nuevos argumentos.