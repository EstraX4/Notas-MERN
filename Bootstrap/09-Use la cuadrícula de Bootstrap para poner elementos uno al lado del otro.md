
# Use la cuadrícula de Bootstrap para poner elementos uno al lado del otro

Bootstrap utiliza un sistema de cuadrícula de 12 columnas receptivo, lo que facilita colocar elementos en filas y especificar el ancho relativo de cada elemento. La mayoría de las clases de Bootstrap se pueden aplicar a un `div`elemento.

Bootstrap tiene diferentes atributos de ancho de columna que usa según el ancho de la pantalla del usuario. Por ejemplo, los teléfonos tienen pantallas angostas y las computadoras portátiles tienen pantallas más anchas.

Tomemos, por ejemplo, la `col-md-*`clase de Bootstrap. Aquí, `md`significa medio, y `*`es un número que especifica cuántas columnas de ancho debe tener el elemento. En este caso, se está especificando el ancho de columna de un elemento en una pantalla de tamaño medio, como una computadora portátil.

En la aplicación Cat Photo que estamos creando, usaremos `col-xs-*`, donde `xs`significa extrapequeño (como la pantalla de un teléfono móvil extrapequeño) y `*`es el número de columnas que especifica cuántas columnas de ancho debe tener el elemento.

Coloque los botones `Like`, `Info`y `Delete`uno al lado del otro anidando los tres dentro de un `<div class="row">`elemento, luego cada uno de ellos dentro de un `<div class="col-xs-4">`elemento.

La `row`clase se aplica a un `div`, y los propios botones se pueden anidar dentro de ella.