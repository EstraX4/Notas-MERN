## String

Este tipo de dato nos permite almacenar una cadena de caracteres.

Podemos definir un  `string`  con:

1.  Comillas simples:

```ts
let myProduct = 'Soda'; //CORRECTO
let comillasDobles = 'Puedo "usar" comillas dobles tambien'; //CORRECTO
let comillaInvalida = 'No puedo 'usar' otra vez una comilla simple'; //INCORRECTO

```

Se pueden usar comillas dobles dentro, más no otra vez comillas simples.

2.  Comillas dobles:

```ts
let myProduct = "Soda"; //CORRECTO
let comillaSimple = "Puedo 'usar' comilla simple tambien"; //CORRECTO
let comillaInvalida = "No puedo "usar" otra vez las comillas dobles"; //INCORRECTO

```

Se puede usar comillas simples dentro, más no otra vez comillas dobles.

3.  Usando backticks:

```ts
let myName = `Frank`;

```

Esta forma de asignar  `string`  trae algunas ventajas:

-   Declarar valores de múltiples líneas:

```ts
let texto = `
    Nunca
    pares
    de aprender :)
`;

```

-   Concatenar dentro del mismo  `string`. Para esto es necesario usar este símbolo del dólar seguido de llaves  `${}`  y escribir lo que queremos concatenar dentro de esas llaves:

```ts
let variableTitulo = "TypeScript";
let summary = `
    title: ${variableTitulo}
`;

```

-   También respeta la indentación:

```ts
let html= `
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  </head>
  <body>
    ...
  </body>
</html>
`;
```