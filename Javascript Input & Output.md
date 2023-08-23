# Javascript Input & Output

### Entorno Web (Navegador):

**Input:**

- En el contexto del navegador, los principales tipos de entrada son los eventos generados por el usuario, como hacer clic en un elemento, mover el mouse, escribir en un campo de entrada, entre otros.
- Los eventos pueden ser capturados y manejados mediante JavaScript utilizando Event Listeners (escuchadores de eventos).

**Output:**

- El principal tipo de salida en un navegador es la modificación del contenido visible en la página web. Puedes modificar el contenido HTML, cambiar estilos CSS o incluso mostrar mensajes emergentes utilizando `alert()` o `console.log()` para imprimir en la consola del navegador.

Ejemplo de captura de clic de botón y cambio de contenido en HTML:

> ```html
> `<!DOCTYPE html> 
> <html> 
> <head> 
>     <title>Input & Output en el Navegador</title> 
> </head> 
> <body> 
>     <button id="miBoton">Haz clic</button> 
>     <p id="mensaje"></p> 
>     <script> 
>         const boton = document.getElementById('miBoton'); 
>         const mensaje = document.getElementById('mensaje'); 
>         boton.addEventListener('click', () => { mensaje.textContent = '¡Se hizo clic en el botón!'; }); 
>     </script> 
> </body> 
> </html>`
> ```

### Entorno Node.js:

**Input:**

- En Node.js, el principal tipo de entrada puede ser la interacción con la línea de comandos (CLI). Puedes leer argumentos de la línea de comandos utilizando `process.argv`, o interactuar con el usuario mediante módulos como `readline`.
- También puedes recibir datos de entrada a través de solicitudes HTTP o interacciones con bases de datos.

**Output:**

- En Node.js, el principal tipo de salida es el registro en la consola. Puedes utilizar `console.log()` para imprimir información en la consola de Node.
- Además, puedes generar archivos de salida, como archivos de registro, archivos JSON o cualquier otro tipo de archivo, utilizando módulos como `fs` (FileSystem) de Node.js.

Ejemplo de salida en la consola en Node.js:

javascript

`// Ejemplo de salida en la consola en Node.js console.log('Hola, mundo desde Node.js');`

En resumen, en el entorno web, el input se refiere a eventos del usuario y la salida se refiere a la modificación de la página web, mientras que en Node.js, el input puede ser interacciones de línea de comandos o solicitudes, y la salida suele ser la consola y la generación de archivos.
