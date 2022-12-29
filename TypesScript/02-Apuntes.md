
## Inferencia de tipos

A partir de la inicialización de la variable TypeScript infiere el tipo que será a lo largo del código y este no puede variar. Por ejemplo:

```ts
let myName = "Victoria";

```

Si bien no indicamos el tipo de dato como se haría de esta manera:

```ts
let myName: string = "Victoria";

```

TypeScript infiere que la variable  `myName`  será del tipo  `string`  y en adelante no podrá tomar un valor que no sea de este tipo de dato.

```ts
myName = 30; 
//Nos señalará como error pues se le quiere asignar un número a una variable de tipo string.
```

## Nombres de variables iguales

TypeScript te indicará como  **error**  aquellas variables con el mismo nombre  **a pesar**  de estar en  **archivos distintos**. Esto no sucederá en entornos preconfigurados como por ejemplo Angular o React, ya que estos trabajan de forma modular o tienen un alcance (scope) para cada variable.

Si deseas trabajar con los mismos nombres de variables en diferentes archivos, puedes crear una función anónima autoejecutada:

```ts
( () => {
    let myName = "Victoria";
})();

```

Lo mismo por cada variable que desees tener el mismo nombre (`myName`  para este ejemplo) deberás crear este tipo de función para evitar que te den estas advertencias.