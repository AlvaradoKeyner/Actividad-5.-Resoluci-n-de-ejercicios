Biblioteca de Componentes UI

Descripción

Una biblioteca de componentes UI reutilizables para una tienda de tecnología, diseñada con CSS avanzado, HTML y JavaScript. Incluye componentes responsivos y accesibles para mostrar computadoras gamer.

Componentes





Botones: Estilos primario/secundario con estados hover y disabled.



Tarjetas: Muestra información de productos con animaciones al hacer hover.



Formulario: Formulario de compra con validación y accesibilidad.



Navbar: Barra de navegación responsiva.



Modal: Ventana emergente para formularios de compra.



Tooltip: Información adicional al pasar el mouse.

Instalación





Clona el repositorio.



Copia los archivos de components/, styles/, y js/ a tu proyecto.



Incluye los estilos en tu HTML:

<link rel="stylesheet" href="styles/variables.css">
<link rel="stylesheet" href="styles/base.css">
<link rel="stylesheet" href="components/[componente].css">



Añade el JavaScript para interactividad:

<script src="js/script.js"></script>

Uso





Botones: Usa <button class="button button--primary">Texto</button> para botones primarios.



Tarjetas: Estructura con card, card__title, card__content, card__image.



Modal: Usa data-modal para asociar botones con modales.



Navbar: Usa <nav class="navbar"> con enlaces.



Tooltip: Añade class="tooltip" data-tooltip="Texto" a elementos.

Ejemplo

Ver demo/index.html, demo/main.html, y demo/catalogo.html para demostraciones.

Notas





Responsive con media queries para pantallas pequeñas.



Accesible con etiquetas <label>, atributos ARIA, y alto contraste.



Usa variables CSS para fácil personalización.



Imágenes externas mantenidas para fondos y tarjetas.