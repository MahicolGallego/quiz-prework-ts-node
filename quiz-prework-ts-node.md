# Quiz de Prerrequisitos para TypeScript y Node.

## Objetivo

El objetivo de este quiz es evaluar tus conocimientos previos sobre JavaScript antes de comenzar con el curso de TypeScript y Node. Responde las preguntas a continuación y envía tus respuestas siguiendo las instrucciones. Este quiz no afectará tu calificación en el curso, pero te ayudará a identificar áreas en las que puedas necesitar repasar antes de comenzar.

## Instrucciones de envío

1. Crea un nuevo repositorio en tu cuenta de GitHub llamado `quiz-prework-ts-node`.
2. Copia las preguntas a continuación y péguelas en el archivo `README.md` de tu repositorio.
3. Responde cada pregunta en su respectiva sección.
4. Realiza un commit y un push de tus respuestas a GitHub.
5. Subir a moodle en el espacio habilitado de semana 1 el link del repositorio en GitHub. En caso de no estar habilitado el envío en moodle, enviar el link del repo a nicolas.picon@riwi.io.

## Preguntas Abiertas (10)

1. **JavaScript Básico:**

   - Describe qué es una función en JavaScript y cómo se declara.

   R/: Una funcion en JAvascript es un trozo de codigo enfocado a dar solucion a una cuestion o
   requerimiento en especifico, haciendo separacion de responsabilidades. puede retornar o no valores.
   generan modularidad y reutilizacion. gozan de su propio ambito/scope de funcion.

2. **Manipulación del DOM:**

   - Explica cómo seleccionar un elemento del DOM y cambiar su contenido.

   R/: Para seleccionar un elemento del DOM se implementa mediante llamando al document
   e implementando algunos de sus metodos para seleccionarlos, como getElementByClassName, ById
   querySelector y demas.

   Para modificar el elemento se modifican sus atributos, tales como, innetHtml, textContent,
   setAttributes y demas.

3. **Programación Orientada a Objetos (OOP):**

   - ¿Qué es una clase en JavaScript y cómo se define una?

   R/: La programacion orientada a objetos es un paradigma mediante el cual
   cualquier cosa de la vida real puede ser llevada/plasmada/abstraida en un software
   para posteriormente generar instancias(objetos) de esta

   class<nameclass> (<parametros>){
   constructor con sus atributos definidos:
   constructor(name){
   this.name=name
   }
   metodos(funciones que indican que puede realizar/acciones)
   }

4. **Eventos en JavaScript:**

   - ¿Cómo se agrega un evento de clic a un botón en JavaScript?

   R/: (btnSeleccionado).addEventListener("click" , () => {})

5. **Variables y Tipos de Datos:**

   - Explica las diferencias entre `var`, `let`, y `const` en JavaScript.

   R/: VAR -> Su scope es global, y si la usamos sin haberla declarado arrojara Undefined. Su contenido puede variar
   LET -> Su scope es de bloque, y si la usamos sin haberla declarado arrojara que no se puede acceder antes de ser inicializada.
   Su contenido puede variar
   CONST -> Su scope es de bloque, y si la usamos sin haberla declarado arrojara puede acceder antes de ser inicializada.
   su contenido no puede variar

6. **Control de Flujo:**

   - ¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?

   R/: Las estructuras de control de flujo son quellas que pueden ser secuenciales, de repeticion o condicionales.
   uso donde necesito realizar acciones repetitivas y/o verificaciones funcionan mediante validaciones para que el
   programa sepa que hacia donde o como fluir

7. **Funciones de Flecha:**

   - Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.

   R/: Una funcion flecha es una funcion declarada, se usa cuando este solo requiere uno o ningun argumento.
   no puede ser utilizada antes de donde se declara, por que estaria en la Deadline

   const saludar = () => {console.log("hola mundo")}

   saludar();

8. **JSON:**

   - ¿Qué es JSON y cómo se utiliza en JavaScript?

   R/: Es un puente de comunicacion entre 2 lenguajes/componentes. Un formato de texto que se utiliza para
   manejar datos estructurados, el mismo es compuesto por el par llave - valor el cual puede ser para
   cualquier tipo de dato de javascript

9. **Promesas:**

   - Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.

   R/: es un tipo de dato objeto mediante el cual se implementan el uso de operaciones que pueden
   resultar resueltas exitosoamente o rechazadas.

   Solicitar los servicios de una API para updates - eliminacion de los datos.

10. **Depuración:**

    - ¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?

    R/:

    - console.log
    - try - catch -> para manejo de errores

## Preguntas de Selección Múltiple (20)

11. ¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?

- A) `var myVariable;`
- B) `variable myVariable;`
- C) `let myVariable;`
- D) `A y C son correctas.`

  R/: C

12. ¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?

- A) `push()`
- B) `pop()`
- C) `shift()`
- D) `unshift()`

  R/: A

13. ¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?

- A) `==`
- B) `===`
- C) `!=`
- D) `!==`

  R/: B

14. ¿Cuál es la salida del siguiente código?

```javascript
console.log(typeof null);
```

- A) `null`
- B) `undefined`
- C) `object`
- D) `number`

  R/: A

15. ¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?

- A) `forEach()`
- B) `map()`
- C) `filter()`
- D) `Todas las anteriores`

  R/: D

16. ¿Qué se entiende por “hoisting” en JavaScript?

- A) Declaraciones de variables y funciones se mueven al principio de su ámbito.
- B) Es un término para describir la eliminación de variables.
- C) Es un método para agrupar varias funciones.
- D) Ninguna de las anteriores.

  R/: A

17. ¿Cuál es la diferencia entre `null` y `undefined` en JavaScript?

- A) `null` significa que una variable ha sido declarada pero no definida, `undefined` significa que no se ha declarado.
- B) `null` es un valor asignado intencionalmente, `undefined` significa que una variable no tiene valor.
- C) `undefined` es un valor asignado intencionalmente, `null` significa que una variable no tiene valor.
- D) No hay diferencia.

  R/: B

18. ¿Cuál es el propósito del método `Array.prototype.map()`?

- A) Modificar el array original.
- B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.
- C) Filtrar los elementos de un array.
- D) Encontrar un elemento en un array.

  R/: A

19. ¿Qué es el `Event Loop` en JavaScript?

- A) Un ciclo que controla las llamadas recursivas.
- B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
- C) Un método para iterar sobre arrays.
- D) Ninguna de las anteriores.

  R/: D x /// correcta -> B Correccion

20. ¿Cuál es la salida del siguiente código?

    ```javascript
    console.log(0.1 + 0.2 === 0.3);
    ```

    - A) `true`
    - B) `false`
    - C) `undefined`
    - D) `NaN`

    R/: A

21. ¿Qué se entiende por `strict mode` en JavaScript?

    - A) Un modo que permite utilizar características experimentales.
    - B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
    - C) Un método para validar datos.
    - D) Ninguna de las anteriores.

    R/: B

22. ¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

    - A) `let obj = {};`
    - B) `let obj = Object.create();`
    - C) `let obj = new Object();`
    - D) A y C son correctas.

    R/: D

23. ¿Qué es un `callback` en JavaScript?

    - A) Una función que se pasa como argumento a otra función.
    - B) Un tipo de variable especial.
    - C) Un método para declarar funciones.
    - D) Ninguna de las anteriores.

    R/: A

24. ¿Cuál es el propósito de `async` y `await` en JavaScript?

    - A) Ejecutar funciones síncronas.
    - B) Manejar operaciones asincrónicas de manera más simple y legible.
    - C) Declarar variables globales.
    - D) Ninguna de las anteriores.

    R/: B

25. ¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

    - A) Arrays
    - B) Strings
    - C) Objetos
    - D) Ninguna de las anteriores.

    R/: C

26. ¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

    - A) `JSON.parse()`
    - B) `JSON.stringify()`
    - C) `toString()`
    - D) `parseInt()`

    R/: B

27. ¿Qué es un `Promise` en JavaScript?

    - A) Una función que se ejecuta inmediatamente.
    - B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
    - C) Un método para declarar variables.
    - D) Ninguna de las anteriores.

    R/: B

28. ¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

    - A) `push()`
    - B) `pop()`
    - C) `shift()`
    - D) `unshift()`

    R/: D

29. ¿Cuál es la diferencia entre `localStorage` y `sessionStorage` en JavaScript?

    - A) `localStorage` almacena datos solo durante la sesión del navegador, `sessionStorage` almacena datos de manera persistente.
    - B) `sessionStorage` almacena datos solo durante la sesión del navegador, `localStorage` almacena datos de manera persistente.
    - C) No hay diferencia entre ellos.
    - D) Ambos almacenan datos solo durante la sesión del navegador.

    R/: B

30. ¿Qué método se utiliza para detener la propagación de un evento en el DOM?

    - A) `event.stopPropagation()`
    - B) `event.preventDefault()`
    - C) `event.stop()`
    - D) `event.cancel()`

    R/: B x // correcta -> A -> No quise escojer obviedad y no lo sabia
