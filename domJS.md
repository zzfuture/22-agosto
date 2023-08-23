## DOM en Javascript

En el contexto de JavaScript, el DOM es una interfaz de programación que permite a los scripts acceder y manipular el contenido, la estructura y el estilo de un documento web.

El DOM se organiza en una estructura de nodos, donde cada nodo representa una parte del documento, como elementos HTML, atributos, texto, comentarios, etc. Estos nodos forman una jerarquía que refleja la estructura del documento.

Aquí hay una descripción general de algunos conceptos clave relacionados con el DOM:

1. **Nodos:** Los nodos son elementos individuales en el árbol del DOM. Pueden ser elementos HTML, atributos, texto, comentarios, etc.

2. **Elementos:** Los elementos son los componentes fundamentales de un documento HTML. Cada etiqueta HTML se convierte en un elemento en el DOM.

3. **Atributos:** Los atributos son pares clave-valor que se asocian con elementos HTML y proporcionan información adicional sobre ellos.

4. **Padre, Hijo y Hermanos:** En la jerarquía del DOM, los nodos pueden tener relaciones de padre-hijo y hermanos. El nodo padre contiene nodos hijos y los nodos del mismo nivel se consideran hermanos.

5. **Manipulación del DOM:** JavaScript permite a los desarrolladores acceder y manipular los elementos y atributos del DOM mediante métodos y propiedades proporcionados por el lenguaje.

Ejemplo de manipulación del DOM en JavaScript:

```html
`<!DOCTYPE html> 
<html> 
<head> 
    <title>Ejemplo de Manipulación del DOM</title> 
</head> 
<body> 
    <h1 id="titulo">Hola, DOM</h1> 
    <p>Este es un párrafo.</p>
    <script>
        const tituloElemento = document.getElementById('titulo');
        tituloElemento.textContent = '¡Hola, DOM modificado!'; 
        const nuevoParrafo = document.createElement('p');
        nuevoParrafo.textContent = 'Este es un nuevo párrafo.';
        document.body.appendChild(nuevoParrafo); 
    </script> 
</body> 
</html>`
```

En este ejemplo, el código JavaScript accede a elementos del DOM, modifica su contenido y crea un nuevo elemento para agregarlo al documento.

En resumen, el DOM en JavaScript es una interfaz que permite interactuar con la estructura y el contenido de un documento HTML, lo que facilita la creación de páginas web interactivas y dinámicas.
