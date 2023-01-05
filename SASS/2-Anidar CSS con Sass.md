# Anidar CSS con Sass

Sass permite el anidamiento de reglas CSS, que es una forma útil de organizar una hoja de estilo.

Normalmente, cada elemento se apunta en una línea diferente para darle estilo, así:

```scss
nav {
  background-color: red;
}

nav ul {
  list-style: none;
}

nav ul li {
  display: inline-block;
}

```

Para un proyecto grande, el archivo CSS tendrá muchas líneas y reglas. Aquí es donde el anidamiento puede ayudar a organizar su código colocando reglas de estilo secundarias dentro de los elementos principales respectivos:

```scss
nav {
  background-color: red;

  ul {
    list-style: none;

    li {
      display: inline-block;
    }
  }
}


```