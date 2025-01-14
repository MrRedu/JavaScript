# Consola

<details align="left">
  <summary>
    <h3>Tabla de contenidos</h3>
  </summary>

<ul>
    <li><a href="#qué-es-la-consola">Descripción</a></li>
    <li>Métodos
    <ul>
      <li>
        <a href="./methods/#log">
          <code>console.log</code>
        </a>
      </li>
      <li>
        <a href="./methods/#info">
          <code>console.info</code>
        </a>
      </li>
      <li>
        <a href="./methods/#warn">
          <code>console.warn</code>
        </a>
      </li>
      <li>
        <a href="./methods/#error">
          <code>console.error</code>
        </a>
      </li>
      <li>
        <a href="./methods/#table">
          <code>console.table</code>
        </a>
      </li>
    </ul>
  </li>
</ul>

</details>

## ¿Qué es la consola?

Es una herramienta fundamental para la depuración y el desarrollo de aplicaciones. Proporciona acceso a la consola de depuración de los navegadores y permite a los desarrolladores mostrar mensajes y datos, facilitando así el análisis y la resolución de problemas en el código.

El objeto console está disponible globalmente en cualquier entorno de ejecución de JavaScript, ya sea en un navegador o en un entorno como Node.js

## Probando la consola
Para abrir la consola, simplemente haz `clic derecho` en cualquier parte de la página y selecciona `Inspeccionar`, luego dirígete a la sección de **Consola**.

![Imagen de consola vacía](https://github.com/user-attachments/assets/79fe8c7a-5bef-403b-b1da-5355dab40459)

> [!NOTE]  
> Ten en cuenta que el acceso a la consola puede variar según el navegador y su versión; sin embargo, los pasos generales son bastante similares.

### Ejemplos de uso
Aquí se presentan algunos ejemplos prácticos de cómo utilizar los métodos del objeto `console`:
```js
console.log('Este es un mensaje normal');
console.info('Información importante');
console.warn('Advertencia: algo podría estar mal');
console.error('Error: algo falló');
```

#### Visualización
![Ejemplo de métodos de la consola](https://github.com/user-attachments/assets/94bea0bf-6063-4efd-8a2b-2972092bf15f)

> [Ver más](./methods) métodos del objeto `console`


## Buenas prácticas
- Uso Moderado: Es recomendable no saturar la consola con demasiados mensajes, ya que esto puede dificultar la identificación de información relevante1.
- Mensajes Descriptivos: Utilizar mensajes claros y descriptivos ayuda a entender mejor el contexto de los datos mostrados. Por ejemplo, en lugar de usar `console.log(data)`, sería mejor usar `console.log('Datos recibidos:', data)`.
- Eliminar en Producción: Es aconsejable eliminar o deshabilitar los mensajes de la consola en el código que se despliega en producción para evitar exponer información sensible y mejorar el rendimiento12.

El objeto console es, por tanto, una herramienta poderosa que mejora significativamente la productividad del desarrollo al facilitar la depuración y el análisis del código.

