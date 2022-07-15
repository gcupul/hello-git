# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecer H6

# Underlines
Underline 1
-----------

Underline 2
============

# Formatos de enfasis
- formato *italica* de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar el *formato italico*  pero tambien **bold** y ~~tachado~~

# Listas
1. Esto es un item
2. Esto es un item
3. Esto es un item

- Esto es un item
- Esto es un item
- Esto es un item

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://wwww.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://logos-world.net/wp-content/uploads/2020/11/GitHub-Logo.png)

# Code Snippets
Codigo en JSON
```JSON
[
    {
        "title": "apples",
        "count": [12000, 20000],
        "description": {"text": "...", "sensitive": false}
    },
    {
        "title": "oranges",
        "count": [17500, null],
        "description": {"text": "...", "sensitive": false}
    },
]
```

Codigo en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi | burgos | 123456 |
| Tomas | Tompson | 123456 |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita

Esto es otro texto que no se relaciona
> Esto es otra cita

