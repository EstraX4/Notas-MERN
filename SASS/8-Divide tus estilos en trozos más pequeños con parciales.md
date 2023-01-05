
# Divide tus estilos en trozos más pequeños con parciales

Los parciales en Sass son archivos separados que contienen segmentos de código CSS. Estos se importan y utilizan en otros archivos Sass. Esta es una excelente manera de agrupar código similar en un módulo para mantenerlo organizado.

Los nombres de los parciales comienzan con el `_`carácter de subrayado ( ), que le dice a Sass que es un pequeño segmento de CSS y que no debe convertirlo en un archivo CSS. Además, los archivos Sass terminan con la `.scss`extensión de archivo. Para llevar el código del parcial a otro archivo Sass, use la `@import`directiva.

Por ejemplo, si todos sus mixins se guardan en un archivo parcial llamado "_mixins.scss", y se necesitan en el archivo "main.scss", esta es la forma de usarlos en el archivo principal:

```scss
@import 'mixins'

```

Tenga en cuenta que el guión bajo y la extensión de archivo no son necesarios en la `import`declaración; Sass entiende que es parcial. Una vez que se importa un parcial a un archivo, todas las variables, mixins y otro código están disponibles para su uso.