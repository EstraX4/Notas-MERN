# Concatenación de cadenas con el operador más igual a

También podemos usar el `+=`operador para concatenar una cadena al final de una variable de cadena existente. Esto puede ser muy útil para dividir una cadena larga en varias líneas.

**Nota:** Cuidado con los espacios. La concatenación no agrega espacios entre cadenas concatenadas, por lo que deberá agregarlos usted mismo.

Ejemplo:

```js
let ourStr = "I come first. ";
ourStr += "I come second.";

```

`ourStr`ahora tiene un valor de la cadena `I come first. I come second.`.