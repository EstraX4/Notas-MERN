
##  CAJAS

> display: block;

    <h1></h1>
    ------------------------------------------------------------
<br>

> display: inline;

    <h1></h1>
    ---------
<br>

> display: inline-block;

    h1 {
        background-color: #a22;
    	display: inline-block; 
    }

--> (es inline pero puede usar propiedades de block)
  

## TOP, RIGHT, BOTTOM, LEFT

    h2 { 
    padding: 1px 2px 3px 4px
    }

**padding-bottom: 3px;
padding-top: 1px;
padding-left: 4px;
padding-right: 2px;**

## MARGIN
`margen entre 2 cajas` **-->** `funciona similar a padding.`

    
    <Caja1>-----margen-----<caja2>

  

## BORDES

    border-radius: 20%;
    border: 10px    solid     blue;
				    dashed
				    double
				    groove
				    inset
				    outset
				    ridge

  
  

##  BOX MODEL

**content** -- line-hight
**padding** -- padding
**border** -- border
**margin** -- margin

## Sombras

  

`box-shadow: 2px 2px 4px 10px 0#000` [para la caja]
`text-shadow: 2px 2px 4px 10px 0#000` [para el texto]

    transform: rotate (-45 deg);

##  Outline

Es como un borde exterior, pero que no ocupa espacio (Osea que si algo esta en ese espacio el borde no se ve)

    outline: 5px solid red;
