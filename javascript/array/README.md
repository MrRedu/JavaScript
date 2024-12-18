# Array `[]`

<details align="left">
  <summary>
    <h3>Tabla de contenidos</h3>
  </summary>

<ul>
  <li><a href="#-¿qué-es-un-array-?">Descripción</a></li>
  <li><a href="./metodos">Métodos</a></li>
  <!-- <li>
    Título para segundo nivel
    <ul>
      <li><a href="">Segundo nivel</a></li>
    </ul>
  </li> -->
</ul>
</details>

## ¿Qué es un Array?

Colección o **agrupación de elementos de cualquier tipo en una misma variable,** cada uno de ellos ubicado con referencia a la posición que ocupa dentro del mismo.

### Creación:

Se puede utilizar el constructor `Array()` para crear objetos **Array**.

```js
const cars = new Array("🚗", "🚓", "🚕", "🚐", "🚛");
```

Pero mayormente se utiliza la notación literal.

```js
const carros = ["🚗", "🚓", "🚕", "🚐", "🚛"];
```

### Estructura:

Los elementos del Array están posicionados por _index/índice,_ (a esto se le llama, _Indexación basada en cero/Indexación desde cero/Zero-based indexing_) esto quiere decir que el primer elemento, tiene la posición [0].

```js
          ["🚗", "🚓", "🚕", "🚐", "🚛"];
//Índice:    0     1     2     3      4

carros[0] // '🚗'
carros[1] // '🚓'
...
carros[4] // '🚛'
```
