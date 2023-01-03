# Modificar datos de matriz con índices

A diferencia de las cadenas, las entradas de los arreglos son mutables y se pueden cambiar libremente, incluso si el arreglo se declaró con `const`.

**Ejemplo**

```js
const ourArray = [50, 40, 30];
ourArray[0] = 15;

```

`ourArray`ahora tiene el valor `[15, 40, 30]`.

**Nota:** No debe haber espacios entre el nombre de la matriz y los corchetes, como `array [0]`. Aunque JavaScript puede procesar esto correctamente, esto puede confundir a otros programadores al leer su código.