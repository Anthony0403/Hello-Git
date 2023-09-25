# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
underline 1
---------------
Underline 2
===============


# Formatos de enfasis
- Formato *italica* de la primer forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primer forma.
- Formato __bold o strong__ de la segunda forma.
- Formato ~~tachado~~.
- Aquí podemos usar muchos diferentes formatos para el texto, así como *italica* o **bold** y también para ~~tachar~~ nuestro texto.

# Listas
1. Estos es un item de lista ordenada.
2. Estos es un item de lista ordenada.
3. Estos es un item de lista ordenada.

- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link html</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo GitHub](https://cdn-icons-png.flaticon.com/512/25/25231.png)

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
  }
]
```
Codigo en javascript
```JAVASCRIPT
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
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi | Burgos | 6541154|
| Tomas | Gutierrez | 7588 |

# Citas
Esto es un texto referente a una cita que pondremos por debajo dle mismo.
> Esto es una cita para el texto

Esto es otro texto que no tiene relacion con el de arriba
> Esto es la cita del segundo texto

# Lineas Divisoras
Esto es de nuevo un texto que va hacer dividido ahora por guiones medios.

---
Esto ahora e sun texto dividido por asteriscos.

***
Esto es un texto dividido por guiones bajos.

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.