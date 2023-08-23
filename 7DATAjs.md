## Valores primitivos

Todos los tipos, excepto los objetos, definen valores inmutables (es decir,  valores que no se pueden cambiar). Por ejemplo (y a diferencia de C),  las cadenas son inmutables. Nos referimos a los valores de estos tipos como "*valores primitivos*".

### Tipo Boolean

`Boolean` representa una entidad lógica y puede tener dos valores: `true` y `false`. Consulta Boolean y `Boolean` para obtener más detalles.

### Tipo Null

El tipo `Null` tiene exactamente un valor: `null`. Consulta `null` y Null para obtener más detalles.

### Tipo Undefined

Una variable a la que no se le ha asignado un valor tiene el valor `undefined`. 

### Tipo Number

ECMAScript tiene dos tipos numéricos integrados: **`Number`** y **`BigInt`**

El tipo Number es un valor en formato binario de 64 bits de doble precisión IEEE 754 (números entre -(253 - 1) y 253 - 1). Además de representar números de punto flotante, el tipo Number tiene tres valores simbólicos: +Infinity, -Infinity y NaN ("Not a Number" o No es un número).

### Tipo BigInt

El tipo `BigInt` es un primitivo numérico en JavaScript que puede representar números enteros con precisión arbitraria. Con `BigInt`s, puedes almacenar y operar de forma segura en números enteros grandes incluso más allá del límite seguro de enteros para `Number`s.

Un `BigInt` se crea agregando `n` al final de un número entero o llamando al constructor.

### Tipo String



El tipo `String` de JavaScript se utiliza para representar datos textuales. Es un 
conjunto de "elementos" de valores enteros sin signo de 16 bits. Cada 
elemento del `String` ocupa una posición en la cadena. El primer elemento está en el índice `0`, el siguiente en el índice `1`, y así sucesivamente. La longitud de una cadena es el número de elementos que contiene.

A diferencia de algunos lenguajes de programación (tal como C), las 
cadenas de JavaScript son inmutables. Esto significa que una vez que se 
crea una cadena, no es posible modificarla.

Sin embargo, todavía es posible crear otra cadena basada en una operación en la cadena original. Por ejemplo:

- Una subcadena de la original seleccionando letras individuales o usando `String.substr()`.
- Una concatenación de dos cadenas usando el operador de concatenación (`+`) o `String.concat()`.
