# **Fundamentos Web: HTML5, CSS3**

## **Creación de un sitio web para plataforma online de contenido digital**

## **Condiciones generales**

* No se permite el uso de librerías y frameworks externos como Bootstrap, Spectre.css o similares.
* Se deberá crear una o más hojas de estilo CSS para aplicar el diseño ndeseado a la web.
* La página web debe visualizarse correctamente en las versiones actuales de Google Chrome, Mozila Firefox y Microsoft Edge.
* No se requiere el uso de interacción mediante JavaScript.

## **Descripción de la práctica**

Nuestro objetivo es construir la estructura web de una plataforma de streaming de contenido digital al estilo de Netflix o HBO para distribuir series y peliculas a cualquier dospisitivo conectado a internet que disponga de un navegador web moderno. Nuestro público es de diferentes edades y condiciones y queremos que disponga de la mejor experiencia de usuario independientemente de tamaño de su pantalla.

Como estamos buscando un producto mínimo viable que podamos poner en marcha enseguida nos centraremos solamente en tres pantallas o secciones.

1. Al llegar a la plataforma se debe mostrar un formulario de login para acceder al contenido. En este formulario se debe implementar:

    * Un campo para el email, que servirá como nombre de usuario
    * Un campo para la contraseña.
    * Un boton para realizar el login y acceder al contenido.
    * Un enlace para iniciar el proceso de recordar una contraseña olvidada.

2. La pantalla principal del contenido contendrá, al menos, los siguientes elementos:
    * Un menú superior, que debe incluir el logotipo de la plataforma, opciones para acceder a la sección de novedades, series, películas o favoritos, un formulario de búsqueda y la opción para cerrar la sesión.
    * Una "rejilla" de películas o series de forma que en cada elemento se muestre una miniatura de la serie/película/episodio. Además, al situar el ratón encima,se mostrará sobre la miniatura información adicional: título, caleficación, año, de publicación y sinopsis resumida.
3. Una ficha detalle de la pelicula/serie/episodio. Debe contener al menos:
    * El mismo menú superior de la pantalla principal.
    * Información básica de la pelicula/serie/episodio: título, calificación, año de publicación, sinopsis completa y listado de actores.
    * Carátula o trailer. El trailer debe poder reproducirse en la propia página
    * "Rejilla" con contenido relacionado, que se usará para los episodios en el caso de una serie o para películas similares en el caso de las películas.

## **Detalles de implementación**

* La estructura de la web tendrá en cuenta las etiquetas de contenido semántico.
* Debéis incluir las media queries necesarias para que el diseño sea responsivo.
* Las animaciones o interactividad propuesta deben realizarse exclusivamente mediante técnicas CSS sin el uso de librerías externas.
* No es necesario hacer multiples páginas distintas para diferentes películas. Cualquier película, serie o episodio enlazará con la misma página de detalle.
* Se valorará el uso de atributos especiales de accesibilidad, microformatos...
