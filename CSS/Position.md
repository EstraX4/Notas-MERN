## POSITION
`STATIC` -> Valor Predeterminado

`RELATIVE`  

`C1`   -> static
`C2`   -> static
`C3`   -> relative
`C4`   -> static

    .caja3 {
    	background-color: green;
    	position: relative;
    	top: 20px;
    	left: 20px:
    }

`top y left` -> tienen prioridad ante `bottom y right`

## z-index
Es para poner un elemento encima de otro.

Si existen 2 o mas elementos con position relative, el que este mas abajo, estara encima del que este mas arriba.

    .Caja1 {
    	z-index: 1;
    }

    .Caja2 {
    	z-index: 2;
    }
El que tenga numero mayor ira encima del menor.

> tip: lo recomendable es poner los z-index de 50 en 50, por si se
> necesita poner alguno entre otro.

Si en un contenedor queremos que el hijo este por encima de este, la unica manera es:

    .contenedor {
    	position: relative;
    }
    *No debe definir z-index
<br>

    .hijo{
    	position: relative;
    	z-index: -1;
    }

## ABSOLUTE
Quita el espacio reservado de este.

`C1`   -> static
`C2`   -> static
`C3 C4`   -> relative
   -> static

*Como el C3 tiene absolute, no hay espacio reservado, asi que C4 puede estar en su mismo sitio.*

`opacity: 0px;` --> Cambia la opacidad