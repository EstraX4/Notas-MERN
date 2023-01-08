
# Agregue iconos de Font Awesome a nuestros botones

Font Awesome es una cómoda biblioteca de iconos. Estos iconos pueden ser fuentes web o gráficos vectoriales. Estos iconos se tratan como fuentes. Puede especificar su tamaño usando píxeles, y asumirán el tamaño de fuente de sus elementos HTML principales.

Puede incluir Font Awesome en cualquier aplicación agregando el siguiente código en la parte superior de su HTML:

```html
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">

```

En este caso, ya lo hemos agregado para usted a esta página entre bastidores.

El `i`elemento se usó originalmente para poner en cursiva otros elementos, pero ahora se usa comúnmente para íconos. Puede agregar las clases de Font Awesome al `i`elemento para convertirlo en un ícono, por ejemplo:

```html
<i class="fas fa-info-circle"></i>

```

Tenga en cuenta que el `span`elemento también es aceptable para su uso con iconos.