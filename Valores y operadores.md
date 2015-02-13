![¿Cómo se programan los ordenadores? Magia.](http://gitbookio.gitbooks.io/javascript/content/assets/intro.png)
# Javascript: Conceptos básicos
**La consola. Valores y tipos de dato. Operadores.**

Oscar Espeso Gil

----------
[TOC]


----------



## ¡¡Comunicación!! 
Elfos, enanos y hobbits no podrían entenderse si no fuera porque en la Tierra Media comparten un lenguaje común.

Lo mismo les pasa a los ordenadores que se comunican en internet. Esa comunicación es posible porque existen lenguajes de programación que son comunes a todos ellos independientemente del país en el que se programen.

Programar consiste en hacer que los ordenadores hagan lo que tú quieres que hagan. Para eso necesitas aprender alguno de los lenguajes que entienden los ordenadores.

Los lenguajes humanos permiten combinar palabras y frases de muchas maneras, para poder expresar ideas muy diferentes.
Los lenguajes de programación, aunque mucho mucho más simples gramáticalmente, siguen la misma filosofía.

Javascript es probablemente uno de los lenguajes más simples y breves en cuanto a su vovcabulario. Al mismo tiempo, también es uno de los más expresivos y flexibles. Permite decir muchas cosas con muy pocas palabras, si sabemos ordenarlas de la forma adecuada.

También es uno de los lenguajes más malinterpretados y peor entendidos por su base de usuarios. Tiene unas cuantas esquinas mal iluminadas, en las que a veces hay trampas muy peligrosas ocultas entre las sombras.
Nosotros vamos a intentar quedarnos en la parte bien iluminada del escenario, quedarnos con lo mejor del lenguaje. Ocasionalmente haremos alguna incursión en las sombras, pero sólo para que sepáis que existen y sepáis evitarlas.

En las siguientes páginas vamos a hablar en detalle de vocabulario, sintaxis y gramática. Sí, aunque no lo creáis la programación en cierto sentido es más de letras que ciencias. 
En lengua nos armamos de un vocabulario básico para poder hablar de como organizar palabras, expresiones y frases. Conceptos como *sujeto*, *predicado*, o *complemento directo* nos resultan a todos familiares. Sin ellos no os hubierais podido entender con vuestro profe de lengua.
 
Lo mismo os va a pasar a vosotros conmigo. Para que nos entendamos cuando os ponga un ejercicio, os explique algo, o me preguntéis algo, tenemos que hablar un lenguaje común. 
El lenguaje del que hablo requiere que os aprendáis algunos términos que se utilizan habitualmente en programación, como: *sentencia*, *expresión*, *operador*, *valor*, *variable*, *función*, etc.

Al principio de cada capítulo encontraréis una lista del vocabulario nuevo que debéis aprender para que nos entendamos. 

Para fijar bien los conceptos y que tengáis un lugar donde buscar el significado de cada uno de ellos, encontraréis un glosario con todos ellos explicados brevemente al final de cada cada capítulo.

Si falláis en la tarea de aprenderos éste vocabulario básico tendremos un problema muy grave. 
Vosotros seréis incapaces de aprobar la asignatura y yo me pondré muy triste :(

¡Venga!, no seáis perezosos. Concededme este capricho y aprendeos el vocabulario básico, que os prometo que va a ser lo único que os tengáis que aprender de memoria.


----------
![El laberinto](http://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/Classical_7-Circuit_Labyrinth.svg/160px-Classical_7-Circuit_Labyrinth.svg.png)

##Acerca de la programación
Aprender a programar está chupado. ¡En serio! ¿No veis lo fácil que es para mi?

¿No cuela?

¡Vaya! Me habéis pillado.

Está bien, admito que aprender a programar no es fácil. Es verdad que las reglas básicas son sencillas, pero a medida que construimos un programa estamos creando nuevas reglas y estás y su interrelación dentro de cada programa tienden (caprichosas ellas) a hacerse más y más complejas a medida que el programa crece. Así que la sensación de estar perdido dentro de su propio laberinto no es extraña para el que empieza a programar.

No os voy a engañar (bueno, a veces sí ;P ). Habrá ocasiones en las que os sentiréis terriblemente frustrados dentro de ese laberinto. Pero hay un truco que debéis recordar siempre. 
![El hilo de Ariadna](https://openclipart.org/image/300px/svg_to_png/189851/Minotaurus.png)
En el Laberinto del Minotauro, Teseo tenía el hilo de Ariadna. Nosotros tenemos el *hilo* de nuestro propio código. Si lo seguimos paso a paso, sin perder la calma y **entendiéndolo**, siempre encontraremos la salida.  

La negrita no es accidental. Entender es fundamental. Para aprender a programar no hay que aprender casi nada de memoria, pero sin entender las reglas y como combinarlas estaremos siempre perdidos. 

Lo que sí que os prometo es que programar es terriblemente divertido cuando le coges el tranquillo. ¡Y tremendamente creativo! Piensa en lo que puedes llegar a hacer. 
Photoshop, Maya, Chrome, Firefox, Twitter, WhatsApp, Youtube, o cualquiera de los videojuegos con los que pasais tan buenos ratos están construidos usando lenguajes de programación. 
¿No os gustaría ser capaces de participar en creaciones como estas?
¡A mi sí!





# Herramientas
## Brackets y jslint
Brackets es un editor para desarrollo web fantástico.  Ha sido creado y está soportado por la comunidad Open Source. 
Es el que os recomiendo para empezar, por su facilidad de uso y configuración, pero hay otros muchos (Sublime Text, Notepad++, etc.). No dudes en investigarlos por tu cuenta si no te convence Brackets.

TERMINAR!!!

## La consola del navegador es vuestra amiga
Todos los navegadores modernos integran varias herramientas de desarrollo para ayudar al programador en su tarea. 

No seáis tímidos y usadlas. No tenéis más que pulsar F12. No importa que navegador estéis usando, todos ellos sucumbirán al hechizo y os mostrarán sus herramientas de desarrollo.

Después de pulsar F12, veréis una pestaña denominada *console* que deberíais tener siempre a la vista cuando estéis programando en javascript.

![Console en Chrome](https://liveutad-my.sharepoint.com/personal/oscar_espeso_live_u-tad_com/_layouts/15/guestaccess.aspx?guestaccesstoken=4Iis6p1RdqQ7YpEvy9PtD3GpY%2bs4yTP2EDz5z4rlQkQ%3d&docid=0766b3202a28f408e9397ac576b7d77ec)
*La consola en Chrome*

![Console en Firefox](https://liveutad-my.sharepoint.com/personal/oscar_espeso_live_u-tad_com/_layouts/15/guestaccess.aspx?guestaccesstoken=RT7JhRHCbGR3Bu33VCPCX%2fhObUl6qOQm%2fVwSbL2O20g%3d&docid=09e12c15fafa84723abbe36a9d68c8b22)
*La consola en Firefox*




---
## Valores, tipos de dato y operadores

* **Conceptos a aprender**
	 * Valores
	 * Tipos de dato
	 * Operadores

Ya, es verdad que el título no es muy atractivo. Tampoco lo sería *cordones, tacos y medias* en un libro sobre futbol ¿no? Pero para jugar cómodo hay que ir bien equipado ¿verdad?

Para programar necesitamos dominar los elementos básicos de los que están hechos los programas. Dentro del mundo del procesador sólo hay datos. Bueno, también hay algo de silicio, pero no seamos tiquismiquis.

Básicamente, programar consiste en leer datos, modificar datos, guardar datos, presentar datos. Los datos lo son todo. Y los ordenadores los representan intérnamente en forma de ceros y unos (cada uno de ellos es 1 bit).

Un ordenador moderno típico posee más de 30 billones de bits almacenados en su memoria volatil (la memoria RAM), y muchísimos más en su memoria de almacenamiento permanente (disco duro o equivalente).

 ![](http://eloquentjavascript.net/img/bit-sea.png)

Para poder trabajar con ese océano de bits sin ahogarse en los datos, podemos separarlos en pequeños trozos de información.
Cada pequeño grupo de bits que representa una unidad de información es un **valor**.

Puede ser un número en la calculadora, el nombre de una persona en una base de datos, o un pixel de una imágen. Aunque todos los valores están compuestos por bits,  cada uno puede jugar un papel distinto en un programa.

Cada valor tiene, por tanto, un **tipo** que determina su *rol* en ese mar de bits.

En Javascript hay 6 tipos de dato básicos: números, cadenas de texto, booleanos (verdadero o falso), objetos, funciones y valores indefinidos.

A continuación hablaremos de cada uno de ellos en detalle


### Numbers. Números
No hay mucho misterio aquí, los valores numéricos son... números. Escribe un número en un programa en Javascript y harás que su grupo de bits (ceros y unos que lo representan) se materialicen en el mundo real, flotando el limbo que hay entre tu frente y la pantalla del ordenador ;)

Por ejemplo,
```
    13
```
es un número y da muy buena suerte.

Javascript usa 64 bits para almacenar cada número (independientemente de cuantos dígitos o decimales tenga). 64 bits permiten representar 2<sup>64</sup> números diferentes. Eso son muchos más de 10<sup>19</sup> (un 1 seguido de 19 ceros) números diferentes.
Sí, es muchísimo. 

Otros lenguajes definen diferentes tipos de números que usan menos y aveces más bits, con la intención de que el programador utilice el tipo de número adecuado, sin ocupar más bits de memoria de los estrictamente necesarios.

Esto era muy importante hace años cuando la memoria de los computadores era muy limitada, pero hoy en día no tiene mucho sentido, a no ser que estemos programando aplicaciones que demanden mucha mucha memoria. En ese caso, y sólo si el programa se va a ejecutar en un móvil, quizás tenga sentido tener cuidado con qué tipo de valores numéricos usamos en nuestro programa.

En cualquier caso, en Javascript no tenemos más opciones, sólo existe este tipo de número.

Los números no exactos se escriben usando un punto para indicar donde empiezan los decimales:
```
9.81
```
Para expresar valores muy grandes o muy pequeos también se puede utilizar notación ciéntifica:
```
2.793e9
```
Este número es 2.793 x 10<sup>9</sup> = 2 793 000 000.

Una de las cosas que los programadores con poca experiencia suelen olvidar es que la forma en la que se almacenan los valores en los ordenadores (grupos de bits) hacen que tengan una determinada *precisión*. O sea,  una precisión **no** infinita. 
Esto puede provocar errores en los cálculos que hacen los programas, a veces muy graves, especialmente si el programa se equivoca a favor del banco al darnos el saldo de nuestra cuenta.

Nosotros no nos vamos a preocupar demasiado por ello. Los programas que haremos durante el curso van a ser fundamentalmente de entretenimiento. Pero conviene tenerlo siempre presente, aún así esta *imprecisión* nos puede jugar una mala pasada.

> ***Recuerda:***
> Si el valor de un número es un entero, no hay problema
> Si el valor de un número tiene decimales, es probable que no sea super, super exacto.

### Aritmética. Conoce a tus enemigos. Digooo... a tus primeros operadores.
Sí, ya lo sé. Estarás pensando: *Esto va de mal en peor. Ahora la clase de programación se está empezando convertir en una clase de matemáticas. Estás acabando de animarme a seguir leyendo, profe...* 

¡Ay! Lo siento. Los datos son ceros y unos, la base del mundo digital (por cierto digital viene de dígito, número). Los números se suman, restan, multiplican y dividen. Tenemos que aprender a hacer operaciones con los datos y éstas son las más básicas.

Además te gustará saber que todos los lenguajes de programación tienen una calculadora incrustada en el... (¡Uy! casi se me escapa) 

O sea que no te voy a enseñar matemáticas de nuevo, eso ya pasó. Lo que te voy a enseñar es como escribir las operaciones para que las haga el programa por ti. Mola ¿no?

Y de paso introducimos el concepto de *operador* que es muy importante en programación.

Un *operador* es una especie de máquina que realiza operaciones. Toma uno o dos valores y produce uno nuevo.

El operador **`+`** toma los dos valores que tiene a izquierda y derecha y los suma, produciendo un nuevo valor. Por ejemplo, si escribimos en un programa:
```
100 + 7
```
> **Recordatorio**:
>  Puedes probar todos los ejemplos que voy a poner a partir de ahora directamente en la consola de Chrome o Firefox. De hecho, te recomiendo que lo hagas :)

El operador **`+`** producirá el valor `107`. De hecho, en el programa donde la expresión anterior esté escrita, al ejecutarse el programa, ésta expresión será sustituida por valor del resultado.
Se dice que el operador **`+`** *devuelve* el valor de la suma de los dos números y *sustituye a la expresión.

Este concepto de sustitución será muy importante más adelante, cuando hablemos de funciones que devuelven un valor. Los operadores y las funciones, aunque tienen una sintaxis muy diferente, tienen esto en común, la capacidad de *devolver* un valor.

Creo que no hace falta que te explique lo que hacen los operadores **`-`** (resta), **`*`** (multiplicación), y **`/`** (división), ¿verdad?

Si creo que hace falta que tengáis claro que ocurre primero cuando escribimos expresiones como:

```
3 + 5 * 4
```
Aquí la regla es igual que en matemáticas, por si no te acuerdas: multiplicación y división siempre se hacen primero. O sea que la expresión anterior *devuelve* `23`.

Si queremos cambiar este orden de precedencia debemos usar paréntesis. Así:

```
(3 + 5) * 4
```
*devuelve* `32`.

Nos queda un operador aritmético por ver: `%`
No, no calcula el tanto por ciento. Es el operador *módulo* y *devuelve* el resto de la división del valor que tenga a su izquierda entre en valor que tenga a su derecha.
O sea que 

```
10 % 6
```
*devuelvolverá* 4, que es el resto de la división. Y

```
6 % 2
```
*devolverá* 0, ya que `6 / 2` es `3` exáctamente y el resto es `0`.

La prioridad del operador **`%`** es la misma que la de los operadores  **`*`**, y **`/`**.

### Números especiales
En Javascript hay tres valores especiales a los que se considera números, aunque no se comportan como números normales:
`Infinity`, `-Infinity` y `NaN`.

`Infinity - 1` devuelve `Ìnfinity`, lo mismo que `Infinity + 1`. Si eres de los que les va las emociones duras que tienen que ver con las matemáticas del infinito, no pongas demasiada confianza en estos números, no operan de forma matemática correcta. Existen únicamente para comprobar si hemos dividido un valor numérico entre cero, que como sabrás es una operación que hay que evitar a toda costa en la mayoría de los casos. Y si no hay forma de hacerlo, al menos nuestro programa debería ser capaz de detectar esa situación para corregirla, o escupir un error y admitir ante el usuario que no somos lo suficientemente buenos como programadores y aceptar la vergüenza. 

Nuestro siguiente amigo es `NaN` que es el valor que toma algo que debería ser un número pero que resulta que no lo es. Obtendrás este resultado cuando intentes dividir `0`entre `0`, sumar `Infinity`y `-Infinity` u operaciones similares que no den un resultado preciso o con significado.

### Strings. Cadenas de texto
Las cadenas de texto, cadenas o *strings* en inglés, son el tipo de valor que nos permite explayarnos y aburrir al personal con textos tan largos como queramos.

Una cadena de texto se distingue de todos los demás valores porque va encerrada entre comillas simples o dobles:

```
"Mi mama me mima mucho"
'Mi profe me obliga a pensar demasiado' 
```
Cualquiera de las dos opciones es válida, siempre que si se abre una cadena con un tipo de comilla se cierre con el mismo tipo.

Mete cualquier valor entre comillas y Javascript lo convertirá en un valor de cadena de texto. Así que ten cuidado porque `5` es un número y `"5"` es una cadena de texto, aunque para ti, ser humano, pueda significar lo mismo, para Javascript no.

Sin embargo, hay algunos valores que es más difícil expresar como cadena de texto. ¿Como pongo unas comillas dentro de una cadena? ¿Así?

```
"Me pregunto cómo se pondrán unas " dentro de una cadena de texto"
```

Las comillas sirven precisamente para indicar que lo que hay entre ellas es una cadena. Si el intérprete de Javascript se encuentra dentro de un par de ellas con otras comillas del mismo tipo, ¿no pensará que estoy cerrando la cadena, indicando que ahí es donde acaba la misma? 
Correcto esto es lo que pasa. 
Si hay más texto detrás, producirá un error, porque cualquier texto fuera de un par de comillas es interpretado como una palabra reservada, un nombre de variable o una función. 

Es aquí donde nos podemos aprovechar de que hay dos formas de poner límite a una cadena de texto. Si queremos poner unas comillas dobles dentro de una cadena podemos utilizar la comilla simple como delimitador:
```
'Me pregunto cómo se pondrán unas " dentro de una cadena de texto'
```
Si queremos utilizar una comilla simple dentro de una cadena, podremos hacerlo, siempre que hayamos usado comillas dobles para delimitar dicha cadena de texto.

```
"Me pregunto cómo se pondrá una ' dentro de una cadena de texto"
```

Los dos ejemplos de cadena anteriores son válidos y no producen ningún error, como el anterior a ellos.

Existe un tercer método de resolver este dilema, y éste es la solución también otros problemas que nos podemos encontrar al querer escribir ciertos caracteres dentro de una cadena de texto. Uno de ellos es el *caracter de salto de línea*, el otro es el de *tabulador*. Sí, ambos se codifican como cualquier otro caracter internamente, pero para expresarlos en Jvascript necesitamos dos. El primero ha de ser la *contrabarra* (`\`), también denominado caracter de *escape*.

* Si después de el *caracter de escape* escribimos una n, o sea si esceibimos `\n`, estarémos introduciendo un salto de línea en la cadena de texto.
   Por ejemplo:
  ```
  "Esto es una línea. \nY esto es otra, dentro de la misma cadena de texto."
  ```
  El texto contenido en la cadena anterior sería en realidad:
  
  ```
  Esto es una línea.
  Y esto es otra, dentro de la misma cadena de texto.
  ``` 
* Si después de el *caracter de escape* escribimos una t, o sea si esceibimos `\t`, introduciremos un tabulador en la cadena de texto.

  ```
  "\t Me gusta el texto tabulado."
  ``` 
  
  O sea:
  
  ```
		  Me gusta el texto tabulado.
  ```
  Fíjate en que el texto anterior empieza más a la derecha de lo normal, porque tiene un tabulador delante.
* Y si detrás de esa *contrabarra* ponemos unas comillas, `\"`, impediremos que se acabe la cadena de texto (si la habíamos empezado con con unas comillas). Lo mismo se aplica a la comilla simple, `'`.
Por ejemplo:

 ```
 "Y Pedro dijo: \"¡Que viene el lobo!\", pero ya nadie le creyó..."
 ```
Produciría una cadena como esta:  

  ```
  Y Pedro dijo: "¡Que viene el lobo!", pero ya nadie le creyó...
  ```

###Concatenado de cadenas
Concatenar significa unir. Aunque parezca confuso, todos los lenguajes suelen utilizar el operador `+` para unir también cadenas:
```
"con" + "ca" + "te" + "nar"
```
Devolverá la cadena:
```
concatenar
```
Puede surgirnos la duda de cuando `+` funciona como operador suma y cuando como operador de concatenación. 
Es muy fácil, sólo si está rodeado de valores numéricos funciona como *operador suma*.
Si cualquiera de los valores a izquierda o derecha es una cadena funcionará como *operador de concatenado.*

### Booleans. Verdadero o falso.
<iframe width="560" height="315" src="https://www.youtube.com/embed/2OgWHeQ0UlY" frameborder="0" allowfullscreen></iframe>
https://www.youtube.com/watch?v=2OgWHeQ0UlY
¿Conocéis el famoso acertijo del pais donde todos los ciudadanos pertenecen a una de estas dos categorías: los que siempre dicen la verdad, y los que siempre mienten?
Un viajero se encuentra con dos des estos paisanos al llegar a una bifurcación del camino que lleva a la capital. 
Previamente le habían advertido que estos dos sujetos suelen merodear por allí  y que uno de ellos es de los siempre sinceros y el otro es de los que siempre mienten. No son mala gente pero se entretienen echándose unas risas a costa de los desorientados turistas.
Así que cuando nuestro avezado viajero llega a su altura ya tiene pensada cual es la pregunta que les va a hacer para averiguar cual es el camino correcto. Esta vez los que quedan desorientados son ellos.

Javascript, como cualquier otro lenguaje de programación es de los que siempre son siceros, pero para poder fiarse de sus respuestas hay que entender un poco como piensan los ordenadores.

Boolean es el tipo de los valorres que sólo pueden ser verdadero (`true`) o falso (`false`). Como podéis imaginar este tipo de valores son muy útiles para tomar decisiones y más adelante veremos como construir estructuras que permitan a nuestros programas tomarlas con criterio y coherencia.

Ten en cuenta que *verdadero* y *falso* son dos estados que pueden asociarse con *sí* y *no*, *endendido* y *apagado*, *activo* e *inactivo*, o cualquier variable que solo puede tener dos valores opuestos entre sí. Así que aunque sólo tengan dos posibilidades, los valores *booleanos* pueden llegar a ser muy útiles, y son fundamentales en cualquier lenguaje de programación.

Los valores booleanos normalmentes son el resultado de algún tipo de operación, usualmente comparaciones. Para realizar este tipo de comparaciones se utilizan los operadores de comparación binarios.


### Operadores de comparación

Los operadores de comparación son la herramienta básica de pensamiento para un programa. Para tomar decisiones, nosotros los humanos, y los ordenadores comparamos cosas. Si la comparación nos satisface (devuelve `true`) hacemos una cosa y si no, hacemos otra.

Los símbolos `>` y `<` son dos de estos operadores y, como ya sabéis, significan, ***mayor que*** y ***menor que***, respectivamente. Su utilización tiene como resultado (*devuelven*) un valor *booleano*.

`3 < 5` devuelve `true`. Mientras que `10 < 2` devuelve `false`.
`3 > 5` devuelve `false`, `10 > 2` devuelve `true`.
`(8 + 3) * 11 > 120` devuelve `true`
> Compruébalo en la consola del navegador

También tenemos el operador ***mayor o igual que***: `>=`, y el operador ***menor o igual que***: `<=`. ¡Cuidado! No debe haber ningún espacio entre el `>` o el `<` y el `=`.

`3 <= 3` devuelve `true`. Mientras que `3 < 3` devuelve `false`. 
Sí, ya sé que este último ejemplo no parece muy útil, pero creedme, esta distinción es necesaria, como veremos más adelante.

Otros dos *operadores binarios* dignos de mención, que tienen como resultado un *valor booleano* son los operadores ***igual que***, `==`  y ***no igual que***, `!=`.

Prueba los siguientes ejemplos en la consola. ¿Todavía no has aprendido a usarla ¿A qué estás esperando? ¡Comprueba que no te engaño!

`3 == 10 - 3` devuelve `true`. 
`2 + 2 == 5` devuelve `false`.
`7 != -7` devuelve `true`.
`"Pedro" != "Manuel"` devuelve `true`.
`"concatenar" != "co" + "can" + "te" + "nar"`

Inventa tus propios ejemplos y ponlos en práctica en la consola. Hazme caso. Puede que todo lo que te he contado hasta ahora te parezca muy sencillo. Pero estoy seguro de que te vas a llevar alguna sorpresa si lo pones en práctica.

Programar es una de esas disciplinas en las que la teoría te enseña poco si no la pones en práctica. ¿No me crees? Sigue probando en la consola. 
Una de las dificultades más grandes para el que empieza a programar es aprender a pensar usando la lógica que utilizan los propios ordenadores (y cualquier máquina en general). Los séres humanos no solemos pensar así. Los razonamientos lógicos se vuelven escurridizos en cuanto tenemos que dar más de dos o tres pasos. Por eso es fundamental que practiques, para acostumbrarte a pensar de esta manera cuando te enfrentes con un programa.

`"3" == 3` devuelve `true`
`"7" != 7` devuelve `false`
`"" == 0` devuelve `true`
`"true" == true` devuelve `false`
`0 == false` devuelve `true`
`" " == false` devuelve `true`

¡Oye! ¡Oye! Espera un momento. Esto sí que no lo entiendo.

Ya te lo dije, la teoría suena siempre bien, es cuando intentamos ponerla en práctica cuando aparecen casos extraños que no conseguimos entender.

Este comportamiento *extraño* es el origen de alguno de los grandes quebraderos de cabeza con los que se puede encontrar un programador de Javascript. Tiene que ver con la conversión automática de tipos de valor, de la que hablaremos más adelante. 

Si la menciono aquí es sólo para demostrarte que que no todo es tan evidente como aparece en los libros de texto, y que uno debería siempre tener la consola al lado para ir probando las cosas. Probar más cosas de las que aparecen en los ejemplos, y preguntar a alguien que sepa cuando aparezcan casos extraños como estos. 

Se aprende más de lo que uno no entiende que de lo que uno entiende a la primera. Si se trabaja para entenderlo, claro está.

### Operadores lógicos
Se llaman operadores lógicos a aquellos que operan sobre valores booleanos y devuelven un valor booleano.
En Javascript hay tres: *and*, *or* y *not*. Se utilizan para *"razonar"* sobre valores booleanos, o expresiones que los produzcan.

Todavía no podemos razonar mucho con ellos porque no hemos visto lo que son las variables, los condicionales, ni otras expresiones que nos permitan construir razonamientos complejos. Pero conviene ir familiarizándose con la forma de *"razonar"* de los lenguajes de programación, porque te va a parecer muy marciana al principio.
Primero veamos como se escriben:

* El operador ***and*** se escribe como **`&&`** y sólo devuelve `true` si los valores que tiene a izquierda y derecha son `true`.
* El operador ***or*** se expresa como **`||`** (AltGr + 1) y devuelve `true` si alguno de los valores es `true`. Sólo devuelve `false` si ambos son `false`.
* El operador ***not***, que se escribe como **`!`** (un signo de admiración con el punto hacia abajo), es un operador *unario* porque sólo opera sobre un valor, el que tenga a su derecha, y devuelve el valor contrario. 
Si opera sobre un valor que es `true` devuelve `false` y si opera sobre un valor que es `false` devuelve `true`


Por ejemplo:
`true && true` devuelve `true`
`false && false` devuelve `false`
pero `true || false` devuelve `true`
`false || false` devuelve `false`
aunque `true || true` también devuelve `true`

Pero es que esto es muy fácil, vamos a introducir el operador *not* a ver si lo complicamos un poco:
`true && !true` devuelve `false`
`!false && !false` devuelve `true`
`true || !true` devuelve `true`. ¿No os recuerda esto a Shakespeare? Vale, sí, ... es verdad que a veces se me va de las manos.

¿Y esto que devolverá?
`true && !((false && true) || true)`

Sí, se pueden usar paréntesis para fijar prioridades. Por cierto, si no se usan paréntesis `!`tiene la máxima prioridad, después va `&&` y por último `||`.
¿Qué devolverá la expresión anterior si le quito los paréntesis?
`true && !false && true || true`

En este caso, está bien que lo pruebes en la consola, pero aprenderás más si intentas pensarlo de cabeza primero. Y si no aciertas, intenta entender por qué no es como tú pensabas.

Pero no nos desviemos del objetivo y veamos un uso de los operadores de comparación que sí que podemos entender ahora: averiguar si cierto valor está dentro de un rango concreto. Supongamos que el valor que queremos comprobar es el resultado de una operación que nos resulta muy difícil calcular y queremos incluirlo en una expresión que nos diga si está entre 0 y 10:
```
((20 % 3) * 5 - 3) > 0 && ((20 % 3) * 5 - 3) < 10
```
Si es mayor que 0 **y** (*and*) menor que 10. Estará dentro de nuestro rango.
Este tipo de operación se utiliza mucho así que conviene que la practiques. ¿Qué devolverá la expresión anterior?

## Valores no definido y nulo: `undefined` y `null`
Hay dos valores especiales, `undefined` y `null` que sirven para indicar la ausencia de un valor significativo. Son valores de pleno derecho, pero no contienen información. Hablaremos más de ellos cuando empecemos a trabajar con variables, pero te los presento ahora. Los veras muchas veces, la mayoría de ellos te indicarán que has hecho algo mal. Algunas veces los usarás para averiguar en que estado está tu programa para poder tomar alguna decisión al respecto.

La diferencia entre `undefined`y `null` no es significativa en Javascript. En otros lenguajes lo es y es útil. Pero en Javascript se cometió un error de diseño del lenguaje que impide que esta distinción sea útil, así que la mayoría de las veces los trataremos como si fueran intercambiables.


## Conversión automática de valores

Este es uno de los apartados que más disgustos le da al recién llegado al mundo de la programación. No es porque sea difícil de entender, sino más bien porque cuando se explica no parece demasiado importante y se olvida.

No olvides lo que te voy a contar. Después del olvido de un punto y coma o un paréntesis, ignorar la conversión automática de tipos de valor es una de las causas más habituales de los errores de un programa.

¿Qué hace Javascript cuando le decimos `"5" - 1`? ¿Acaso tendría que hacer algo? Si no lo ves, necesitas dar un paso hacia delante y mirar fijamente a las comillas que rodean el 5. Nuestro cerebro es un procesador tremendamente complejo y tiene una capacidad que los ordenadores no tienen. Es capaz de filtrar e ignorar la información superflua. A nosotros nos da igual que un 5 sea una cadena de texto o sea un número. Un 5 es un cinco, lo escribamos como lo escribamos.

Sin embargo, el ordenador para poder realizar la operación, necesita que los dos valores que están a izquierda y derecha sean del mismo tipo, en este caso necesita que sean números. 

Afortunadamente, hemos sido capaces de incluir en los lenguajes de programación mecanismos automáticos de conversión de tipos para que los ordenadores se parezcan a nosotros un poquito.

No cantes victoria. El sistema no es perfecto y a veces hace cosas raras. Por eso hay que conocer como funciona, para poder anticiparnos y hacer la conversión nosotros si sabemos que Javascript no va a ser capaz de hacerlo correctamente.
Veamos algunos ejemplos:

`"5" * "3"` devuelve `15`, de momento todo bien.
`"5" - 1` devuelve `4`. Fíjate que funciona como cualquiera esperaría, incluso operando con dos valores de tipos diferentes. 

Pero a veces pasan cosas raras:
`"5" + 1` devuelve `"51"`, ¿sorprendid@?
¿Recuerdas que te conté que el operador `+` concatena en lugar de sumar cuando alguno de los valores que hay a su alrededor es una cadena?. Esta vez había que hilar fino. Como ves hay que estar muy pendiente.

Ahora viene una buena:
`10 * null` devuelve `0` y esta es bien gorda. Ese `null`, si está ahí, significa que algo que ha ido mal y Javascript no ha sido capaz de encontrar o calcular el valor correcto en alguna operación que estábamos intentando realizar. 
En otros lenguajes de programación cualquier operador actuando sobre un valor `null` produciría un error informando que no sabe qué hacer con él.
Javascript no es perfecto. Ningún operador actuando sobre `null` da error. El navegador lo hace lo mejor que puede convirtiéndolo a un valor que sirva para realizar la operación y tú como programador no te enteras de que hay algo que va muy mal.

Por eso no hay que fiarse de la conversión implícita o automática. Es mejor que permanezcamos atentos y realicemos la conversión manual nosotros mismos. Todavía no te voy a explicar como hacerlo. Lo haré más adelante cuando te haya presentado las herramientas que permiten hacerlo de la forma correcta. Pero me interesa mucho que seas consciente desde ya de que nos podemos encontrar con problemas si dejamos que Javascript haga conversiones de valores por su cuenta.

### Los operadores  `===` y `!==`
Unos pocos párrafos más arriba te ponía estos ejemplos:
`"3" == 3` devuelve `true`
`"7" != 7` devuelve `false`
`"" == 0` devuelve `true`
`0 == false` devuelve `true`
`" " == false` devuelve `true`

Ahora que hemos hablado de la conversión automática de valores, seguro que los entiendes mejor. Javascript decide en todos ellos que valor convierte a otro tipo para poder compararlos de una forma coherente. Pero coherente no siempre significa correcta. 

Ya te he comentado que casi siempre es mejor evitar la conversión automática de valores.
En el caso de las comparaciones de igualda existe una forma de evitarla, utilizando los operadores ***exactamente igual que***, **`===`**, y ***exactamente no igual que***, **`!==`**.
De hecho, te recomiendo que siempre utilices estos, en lugar de `==` o `!=`, a no ser que tengas una razón de peso para permitir la conversión automática de valores.

Así 
`"3" === 3` devuelve `false`
`"7" !== 7` devuelve `true`
`"" === 0` devuelve `false`
`0 === false` devuelve `false`
`" " === false` devuelve `false`
Espero que estés de acuerdo conmigo en que estos resultados son mucho más correctos, y sobre todo predecibles usando un poco de materia gris, que los primeros.
 

## Otros operadores 
Hay más operadores de los que hemos visto en este capítulo, pero de momento nos basta con estos y con que sepas que algunos de ellos no son símbolos *extraños* como los que hemos visto hasta ahora. Algunos son palabras.

Este último es el caso del operador `typeof`, que opera sobre un sólo valor (y por tanto es *unario*). Devuelve una cadena de texto que describe el tipo del valor sobre el que opera. Y así cerramos el círculo con un operador que sirve para saber de que tipo es un valor concreto. Puede no parecer muy útil ahora, pero nos demostrará que lo es en cuanto estudiemos las variables y todo lo que podemos hacer con ellas.

Ejemplos:
`typeof 7.3` devuelve `"number"`
`typeof "Hola mundo!"` devuelve `"string"`
`typeof true` devuelve `"boolean"`

## Otros valores
No, no hemos terminado. Quedan otros tipos de valores por ver, y son muy importantes para el lenguaje Javascript. Pero se está haciendo tarde y este capítulo se está haciendo ya muy largo. 

Estoy hablando de las funciones, los objetos y los arrays, entre otros. Se podría decir que no se puede programar sin ellos. 

Pero tampoco se puede programar sin los que hemos visto, y en realidad son la base sobre las que se construyen esos otros tres tipos de valor que he mencionado.
A los que hemos visto se les suele llamar tipos de valor *básicos* o *primitivos*, precisamente por ello.

Y aunque te parezca que hemos aprendido poco, si has llegado hasta aquí entendiéndolo todo hemos avanzado mucho hacia el objetivo de aprender el lenguaje. Para que nos entendamos, has aprendido a decir "Papa", "Mama" y "quiero". 

No las menosprecies, con esas tres palabras se pueden conseguir muchas cosas cuando tienes apenas unos meses de vida. Y son sólo el principio, a partir de ese momento el proceso de aprendizaje se expande de forma exponencial.










## Cortocircuitado de operadores lógicos
No, no vamos a dejar *matrix* colgada. Es sólo una forma de hablar. 
Hemos visto como la conversión automática de valores puede jugarnos malas pasadas, pero también puede jugar a nuestro favor y vamos a ver una forma de aprovecharnos de ello.

Los operadores lógicos `||` y `&&` actúan sobre valores booleanos, como ya hemos visto. Si los valores que tienen a derecha e izquierda no son de este tipo, entra en juego la conversión automática de valores. 
