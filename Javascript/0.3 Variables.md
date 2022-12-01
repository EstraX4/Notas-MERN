# variables

    recipiente = "Cosa";

## Tipos de datos

    String = "Cadena de texto";
    number = 19;
    Booleano = true o false;
    
## Casos especiales de datos
`var` -> Mucho alcance
`let` -> Alcance limitado **(Ej: Un bloque)**

`const` -> No cambian su valor, valor unico.

`let numero;` -> como la variable no tiene valor, este sera undefined.
`const` -> Hat que inicializala siempre.

`Scope` -> si un let esta dentro de un bloque solo funciona en ese bloque.

`Hoisting` -> Manera general de referirse a como funcionan los contextos de ejecución en javascript (especialmente las fases de creación y ejecución)

`null` -> Definida pero vacia.
	ej:  `let numero = null;`

`NaN` -> Not a Number

	Ej:	
	
    let numero = 5;
    let numero2 = "Juan";
    `alert( numero * numero2 )`   
	
-> No se multiplican porque una variable, no es un numero NaN.