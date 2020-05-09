## Explica los siguentes conceptos con tus propias palabras. (no más de tres líneas por respuesta).

* HTML:

* CSS:

* Git:

* Arreglos:

* Objetos:

* Variables:

* Métodos:

* DOM:

* Atributo de un tag HTML:

* Selector CSS:

* Un función constructora:

HTML: Es la "estructura" de una página web, es decir, es lo que le da el cuerpo y contenido a una pagina web. Haciéndo una comparación con una obra en construcción. HTML sería la estructura de hormigon, las columnas, vigas, losas, paredes, etc. Es la que se encarga del contenido de la pagina.

CSS: Es la que se encarga de darle un estilo estético a una página web, donde se le dan las dimensiones a cada elemento del HTML, se elije la paleta de colores, las fuentes, tamaños y tipos de fuente. Además es la que se engarga de darle un estilo adaptable a la pagina dependiendo el dispositivo de salida. Es decir, adaptarlo a la resolución. Usando la comparación de la obra en construcción. CSS sería algo así como los materiales de los cuales se le da el estilo, decoración, pintura, tipos de puertas, piso, etc. JS sería algo así como las instalaciones de gas, sanitarios y electricos, les da uso y habitabilidad.

Git: Es un sistema de control de versiones, permite registrar todo el historial de cambios de un proyecto. En estos están los "repositorios", que es todo proyecto que está siendo seguido por git y los "commit" son los "cambios" que se han hecho, se hace un "commit" cada vez que se hace un cambio en el proyecto y donde el programador especifica qué cambio y porqué.

Arreglos: También conocidas como "vectores" o "Array", un array es un tipo de dato donde puede almacenar multiples datos de distintos tipos, ya sean numericos, cadenas de texto, booleanos, objetos u otros arrays. Los array vienen con la particularidad de tener un largo y estar ordenados en "numero de indice" que comienza desde el "0". Imaginemos este como un tren de carga, donde en cada vagón carga un tipo de dato diferente, estos vagones vienen numerados a partir del "0" en adelante. Para acceder al tipo de contenido, se llama al array y al numero de indice, por ejemplo " array[0] " el cuál accede al primer "vagon" del tren, es decir, al primer dato del arreglo. " array[4] " accede al 5to elemento, y así siempre teniendo en cuenta que su indice comienza desde el 0.

Objetos: Un objeto es un elemento que tiene distintas propiedades asociadas o funcionalidades, es decir; de varias variables o funciones, también denominadas "propiedades" y "métodos" cuando nos referimos a objetos. Los objetos pueden tener, al igual que los arreglos, muchos tipos de datos, con la caracteristica que estos datos no están indexados y estos valores están almacenados en variables que para acceder a estos datos hace falta llamar al objeto y luego a la propiedad separadas por un punto, por ejemplo "objeto.propiedad". En el ejemplo anterior se llamó al objeto a través del método de notación de puntos, pero también se puede acceder a través del método de notación de corchetes. La notación de puntos solo funciona con nombres de propiedad que son nombres identificadores válidos, uno no-valido sería una propiedad con carácteres que no están permitidos para las variables o por papabras separadas por un espacio. Por ejemplo "objeto["nombre de la propiedad"]".

Variables: Las variables son una manera de almacenar información y luego utilizarla mas adelante en nuestro código. Es decir que, en esta variable podemos hacer referencia a algúna función, suma, resta u otro dato y utilizarlo indefinidamente. Pero cuidado que las variables "var" permiten sobreescritura, a difenrencia de "const" que cumple con la misma función pero que no permite sobreescritura. Y existe también "let" que cumple también la misma función, permite sobreescritura pero al mismo tiempo tiene un "scope" o una "jurisdicción" limitada al bloque de codigo "padre".

Métodos: Un método es una función especifica y que cumple una función especifica. Dependiendo el tipo de dato, estos métodos funciones vienen integradas dentro de JavaScript. Como JavaScript es un lenguaje de objetos, podemos definir las funciones de los propios objetos que creemos siendo estas funciones métodos de nuestro objeto. En resumen, un método es una función que se pasa como propiedad de un objeto. Se accede a esta función dentro del objeto de la misma manera que se invoca un método de algún tipo de dato como por ejemplo ".lenght", ".reduce()", ".join()", etc.

DOM: Son las siglas de "Document Object Model". El DOM es la estructura de objetos que genera el navegador cuando se carga un documento y se puede alterar mediante Javascript para cambiar dinámicamente los contenidos y aspecto de la página. Es decir, que con funciones, eventos y demás, podemos alterar los elementos del documento HTML.

Atributo de un tag HTML: Los atributos de una etiqueta(tag) HTML, es información extra que se incluye dentro de la etiqueta de apertura del elemento HMTL. Esta información extra sirve para especificar un identificador, clase, dar estilo dentro del mismo HTML, apuntar a un determinado enlace, e incluso; darle propiedades de eventos javascript dentro del propio documento HTML

Selector CSS: Los selectores CSS definen sobre cuales elementos se trabajará con CSS, es decir, a cuales se les estilizará. A estos podes referenciarlos a través de la clase dada en el HTML, la propia etqueta HTML o hasta del propio identificador, además de otros tipos. 

Una función constructora: Una función constructora es una función normal y corriente de JavaScript que se utiliza para definir una especie de plantilla para nuestros objetos personalizados. Esta función recibe determinados argumentos y con estos se les da valor a las propiedades del objeto que irémos a crear con esta "función plantilla". Cuando se invoque a esta función, se lo hará asignando a una variable y con la palabra reservada "new", un nuevo objeto de la clase que ya definimos en la plantilla. Por ejemplo 
"function Plantilla(arg1, arg2, arg3){
	this.arg1: arg1,
	this.arg2: arg2,
	this.arg3: arg3
}"

y luego creamos el objeto nuevo utilizando esta función constructora

"var nuevoObjeto = new Plantilla(valor1, valor2, valor3);"

si hacemos un console.log de nuevoObjeto veremos "{arg1: valor1, arg2: valor2, arg3: valor3}"