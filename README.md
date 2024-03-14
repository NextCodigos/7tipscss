# Ejemplo 1:

Contenedor principal:
<div class="parent">: Este elemento div actúa como el contenedor principal para el contenido centrado.
class="parent": Asigna una clase llamada "parent" a este elemento div para seleccionarlo con estilos CSS.
Contenido (``): Este comentario describe el propósito del contenido (elemento div), pero no tiene efecto visual.
Elemento div interno:
<div>Div dentro parent</div>: Este elemento div anidado es el contenido que se centrará dentro del contenedor principal.
Estilos CSS:

.parent { ... }: Esta regla CSS selecciona todos los elementos con la clase "parent" (que en este caso es el div contenedor principal).
display: grid;: Establece la propiedad display del contenedor principal a grid. Esto habilita el diseño de cuadrícula CSS para el elemento, permitiéndole organizar los elementos secundarios en una estructura similar a una cuadrícula.
place-content: center;: Esta propiedad posiciona el contenido (elementos secundarios) del contenedor de la cuadrícula en el centro del espacio disponible, tanto horizontal como verticalmente.
height: 100vh;: Establece la altura del contenedor principal a 100% de la altura del viewport (vh).
border: 1px solid black;: Agrega un borde negro sólido de 1 píxel al contenedor principal para fines de visualización (opcional).
Funcionalidad general:

Al cargar este documento HTML en un navegador web, verás un borde negro que abarca todo el viewport. Dentro de este borde, el texto "Div dentro parent" se centrará horizontal y verticalmente dentro del contenedor principal (div.parent). Este efecto de centrado se logra utilizando la propiedad place-content: center; en los estilos de cuadrícula CSS.

Notas adicionales:

La línea comentada /* div{ font-size: 66px; } */ no se aplica en este código. Si la descomentas, establecería el tamaño de fuente de todos los elementos div a 66 píxeles.

# Ejemplo 2:

Explicación:

Declaración DOCTYPE:

<!DOCTYPE html>: Esta línea especifica el tipo de documento como HTML5.
Etiquetas HTML:

<html lang="en">: El elemento raíz del documento HTML. El atributo lang="en" indica que el idioma del documento es el inglés.
<head>: La sección head contiene meta información sobre el documento, que no se muestra directamente en el navegador.
<body>: La sección body contiene el contenido que se muestra al usuario.
Metaetiquetas:

<meta charset="UTF-8">: Define la codificación de caracteres del documento para que sea UTF-8, lo que permite 
mostrar correctamente varios caracteres.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Esta metaetiqueta configura el viewport
para ajustar el ancho de la página según el tamaño de la pantalla del dispositivo y establece el nivel de zoom inicial al 100%.
Título:

<title>7 tips css</title>: Establece el título de la página web, que se muestra en la pestaña o barra de título del navegador.
Estilos CSS:

<style>: Define estilos que se aplicarán a los elementos HTML.
h1 { position: relative; }: Esta regla selecciona todos los elementos <h1> y establece su posición en relative. 
  Esto significa que la posición del elemento se establece en relación con su posición normal en el flujo del 
  documento, permitiendo el posicionamiento absoluto de sus pseudo-elementos (como :before).
Pseudo-elemento:

h1:before { content: ""; position: absolute; }: Esta regla selecciona el pseudo-elemento :before de los elementos <h1>.
  Los pseudo-elementos son elementos virtuales que se pueden usar para insertar contenido o efectos de estilo antes o después de un elemento existente.
content: "";: Esta propiedad inserta una cadena de contenido vacía antes del texto real del elemento <h1>.
position: absolute;: Esta propiedad posiciona el elemento :before de forma absoluta en relación con su elemento <h1> contenedor.
  Esto significa que el elemento :before se puede colocar en cualquier coordenada especificada dentro de los límites del elemento <h1>.
En resumen, este código crea una estructura HTML básica con un encabezado (<h1>Mi Título Impresionante</h1>) y aplica estilos CSS 
  para posicionar un pseudo-elemento vacío de forma absoluta antes del texto del encabezado. Si bien este código actualmente no
  crea un efecto visible, sienta las bases para aplicar más estilos usando el elemento :before, como agregar líneas decorativas, 
  íconos o bordes antes del encabezado.


# Ejemplo 3:

Declaración DOCTYPE:

<!DOCTYPE html>: Esta línea especifica el tipo de documento como HTML5.
Etiquetas HTML:

<html lang="en">: El elemento raíz del documento HTML. El atributo lang="en" indica que el idioma del documento es el inglés.
<head>: La sección head contiene meta información sobre el documento, que no se muestra directamente en el navegador.
<body>: La sección body contiene el contenido que se muestra al usuario.
Metaetiquetas:

<meta charset="UTF-8">: Define la codificación de caracteres del documento para que sea UTF-8, lo que permite mostrar correctamente varios caracteres.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Esta metaetiqueta configura el viewport para ajustar el ancho de la página
según el tamaño de la pantalla del dispositivo y establece el nivel de zoom inicial al 100%.
Título:

<title>7 tips css</title>: Establece el título de la página web, que se muestra en la pestaña o barra de título del navegador.
Estilos CSS:

<style>: Define estilos que se aplicarán a los elementos HTML.
h1 { position: relative; }: Esta regla selecciona todos los elementos <h1> y establece su posición en relative. Esto significa
  que la posición del elemento se establece en relación con su posición normal en el flujo del documento, permitiendo el 
  posicionamiento absoluto de sus pseudo-elementos (como :before).
Pseudo-elemento:

h1:before { content: ""; position: absolute; }: Esta regla selecciona el pseudo-elemento :before de los elementos <h1>. 
  Los pseudo-elementos son elementos virtuales que se pueden usar para insertar contenido o efectos de estilo antes o después de un elemento existente.
content: "";: Esta propiedad inserta una cadena de contenido vacía antes del texto real del elemento <h1>.
position: absolute;: Esta propiedad posiciona el elemento :before de forma absoluta en relación con su elemento <h1> contenedor.
  Esto significa que el elemento :before se puede colocar en cualquier coordenada especificada dentro de los límites del elemento <h1>.
En resumen, este código crea una estructura HTML básica con un encabezado (<h1>Mi Título Impresionante</h1>) y aplica estilos CSS 
  para posicionar un pseudo-elemento vacío de forma absoluta antes del texto del encabezado. Si bien este código actualmente no crea 
  un efecto visible, sienta las bases para aplicar más estilos usando el elemento :before, como agregar líneas decorativas, 
  íconos o bordes antes del encabezado.
