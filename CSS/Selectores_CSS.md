## SELECTORES CSS
`selector {` --> **[los elementos, lo que se quiere cambiar]**
`propiedad: valor;` --> **[Lo que se le va a cambiar]**
}

*tip: Todo en html son cajas*

* **Universal**
* **De Tipo**
* **Clases**
* **ID**
* **Por Atributo**
* **Descendiente**
* **Pseudo Clases**

## Universal

    * {
    
    }

--> Selecciona y hace los cambios a todos los elementos.
  

## De Tipo

    H1 {
    }

--> Selecciona elementos de un tipo.
  

## Clases

    <h2  class="Titulo-h2">Titulo</h2>

    .titulo-h2 {
    	color: red; 
    }

--> Selecciona los elementos con Clases
  

## ID

    <h2  id="id-element">Titulo</h2>
<br>

    #id-element {
    	color: red; 
    }

--> Funciona parecido a las clases, pero lo recomendable es con id se use solo para un elemento.
  

## Por Atributo
`<h2  id="id-element"  atributo="atributo"></h2>` --> Puede ser cualquier atributo

    [atributo="atributo"] {
    
    }

## Descendiente

    <h2><p>Parrafo</p></h2>
<br>

    h2 p {
    }

--> Selecciona los p dentro de un h2
  
**(tambien funciona con clases)**

## Pseudo-Clases

    p:hover {
	    color:red; 
    }

--> Cambia al color rojo el parrafo cuando el mouse este encima.
(es un ejemplo, hay mas)