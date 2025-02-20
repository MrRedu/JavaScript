# String `'cadena de texto'`

<details align="left" open>
  <summary>
    <h3>Tabla de contenidos</h3>
  </summary>

<ul>
  <li><a href="#qué-es-un-string">Descripción</a></li>
  <li><a href="./methods">Métodos</a></li>
</ul>
</details>

## ¿Qué es un string? _(cadena de texto)_

Secuencia de caracteres alfanuméricos que se utiliza para almacenar datos textuales. Son útiles para almacenar datos que se pueden representar en forma de texto.

### Creación:

Se puede utilizar el constructor `String()` para crear objetos **String**.

```js
const cadenaDeTexto = new String('Un objeto String');
```

Aunque mayormente se utilizan las notaciones literales.

```js
// Creación con comillas dobles
const cadenaDeTexto = "Una cadena primitiva";
// Creación con comillas simples
const cadenaDeTexto = "También una cadena primitiva";
// Creación con acento grave; este nos sirve para habilitar el uso de expresiones incrustadas y además podemos hacer cadenas de caracteres de más de una línea
const cadenaDeTexto = `Otra cadena primitiva más`;
```

<br>

> [!TIP]
> Lectura recomendada: [`Template literal`]('../../README.md)