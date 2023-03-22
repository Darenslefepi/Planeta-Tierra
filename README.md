# Planeta-Tierra

Las etiquetas semánticas para definir una interfaz de una página web son:

<header>: define el encabezado de la página (no confundir con <head>).
<nav>: define una barra de navegación que incluye enlaces.
<section>: define una sección de la página.
<footer>: define un pie de página o de sección.
<article>: define un artículo, el cual puede tener su propio encabezado, navegación, sección o pie de página.
Ahora que ya conoces las etiquetas semánticas, evita el uso excesivo de <div>.

Ventajas de utilizar HTML semántico
Las ventajas de utilizar un HTML semántico son:

Ayuda a tu sitio a ser accesible
Mejora tu posicionamiento (SEO)
Código más claro, legible y mantenible
Ayuda a buscadores (como Google) a encontrar tu página

Cuáles son las pseudoclases
Una pseudoclase define el estilo de un estado especial de un elemento.

Índice de pseudo-clases estándar.
Sintaxis
selector : pseudoclase { 
    propiedad: valor;
}
:hover
Representa el estado en el cual el cursor está encima del elemento.

Ejemplo
:active
Representa el estado de un elemento que no ha sido visitado.

Ejemplo
:visited
Representa el estado de un elemento que ya ha sido visitado.

Ejemplo
:not()
Representa el estado en el cual no coinciden los selectores que se indiquen.

Ejemplo
:nth-child()
Representa el estado en el cual coinciden los hijos del elemento según el valor indicado.

Valores de palabras clave:

odd: los elementos hijos en posiciones impares.
even: los elementos hijos en posiciones pares.
Fórmula matemática: An+B donde A y B son números enteros.

Cuáles son los pseudoselementos
Un pseudoelemento define el estilo de una parte específica de un elemento.

Lista de pseudo-elementos.
Sintaxis
selector :: pseudo-elemento { 
    propiedad: valor;
}
::before
Sirve para agregar un contenido antes del elemento. El contenido es agregado mediante la propiedad content de CSS.

Ejemplo
::after
Sirve para agregar un contenido después del elemento. El contenido es agregado mediante la propiedad content de CSS.

Ejemplo
::first-letter
Sirve para añadir estilos a a la primera letra del texto de cualquier elemento.