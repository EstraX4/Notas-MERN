
# Use un diseño receptivo con contenedores de fluidos Bootstrap

En la sección HTML5 y CSS de freeCodeCamp creamos una aplicación Cat Photo. Ahora volvamos a eso. Esta vez, le aplicaremos un estilo utilizando el popular marco CSS receptivo de Bootstrap.

Bootstrap averiguará qué tan ancha es su pantalla y responderá cambiando el tamaño de sus elementos HTML, de ahí el nombre de diseño receptivo .

Con un diseño receptivo, no hay necesidad de diseñar una versión móvil de su sitio web. Se verá bien en dispositivos con pantallas de cualquier ancho.

Puede agregar Bootstrap a cualquier aplicación agregando el siguiente código en la parte superior de su HTML:

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"/>

```

En este caso, ya lo hemos agregado para usted a esta página entre bastidores. Tenga en cuenta que es aceptable usar `>`o `/>`para cerrar la etiqueta.`link`

Para comenzar, debemos anidar todo nuestro HTML (excepto la `link`etiqueta y el `style`elemento) en un `div`elemento con la clase `container-fluid`.