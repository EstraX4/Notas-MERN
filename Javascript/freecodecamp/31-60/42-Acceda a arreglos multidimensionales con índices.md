
# Acceda a arreglos multidimensionales con índices

Una forma de pensar en una matriz multidimensional es como una _matriz de matrices_ . Cuando usa corchetes para acceder a su matriz, el primer conjunto de corchetes se refiere a las entradas en la matriz más externa (el primer nivel), y cada par adicional de corchetes se refiere al siguiente nivel de entradas en el interior.

**Ejemplo**

```js
const arr = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  [[10, 11, 12], 13, 14]
];

const subarray = arr[3];
const nestedSubarray = arr[3][0];
const element = arr[3][0][1];

```

En este ejemplo, `subarray`tiene el valor `[[10, 11, 12], 13, 14]`, `nestedSubarray`tiene el valor `[10, 11, 12]`y `element`tiene el valor `11`.

**Nota:** No debe haber espacios entre el nombre de la matriz y los corchetes, como `array [0][0]`e incluso esto `array [0] [0]`no está permitido. Aunque JavaScript puede procesar esto correctamente, esto puede confundir a otros programadores al leer su código.