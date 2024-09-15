<div align="center">
<img src="/logo.png" width="200px">
<h1>TEMC DESIGN</h1>
</div>

## CubeDisplay

### Descripción del Proyecto

CubeDisplay es un proyecto interactivo que combina animaciones en 3D con HTML, CSS y JavaScript. El proyecto muestra una animación de transformación de un cubo a un anillo y finalmente a una serie de elementos que se desplazan, ofreciendo una experiencia visual dinámica y atractiva.

<img src="/2.jpg">

### Características

Animaciones 3D: Utiliza transformaciones y animaciones en 3D para crear una transición fluida entre un cubo, un anillo y una animación final.

CSS avanzado: Aprovecha las capacidades de CSS para crear animaciones complejas y transiciones suaves.

JavaScript interactivo: Maneja las clases de animación y el flujo de la animación mediante JavaScript para cambiar las animaciones en función del estado actual del elemento.

Responsive Design: Se ajusta a diferentes tamaños de pantalla gracias a media queries.

<img src="/1.jpg">

### Estructura del Proyecto

El proyecto está compuesto por tres archivos principales:

1. HTML (index.html): Define la estructura básica de la página y los elementos que serán animados.
2. CSS (presentation.css): Contiene estilos y definiciones para las animaciones en 3D, incluyendo animaciones de cubo, anillo y final.
3. JavaScript (presentation.js): Controla la lógica de las animaciones y la transición entre diferentes estados del cubo.

### Cómo Funciona

Inicio de Animación: La animación comienza con un cubo (clase .cube) que gira en 3D utilizando @keyframes cubeAnimacion.

Transición a Anillo: Al finalizar la animación del cubo, se cambia a una animación de anillo (clase .ring) que gira alrededor de un eje vertical, usando @keyframes ringAnimacion.

Transición Final: Después de la animación del anillo, se transforma a una animación final (clase .final) donde los elementos se dispersan en el espacio, y se muestra el texto del portafolio.

El elemento principal (#shape) cambia de clases y anima sus estados a través de JavaScript, y al final de la animación, oculta el contenedor de portada con una transición de desvanecimiento.

<img src="/3.jpg">

### Requisitos

Un navegador moderno que soporte CSS3 y HTML5.
Conexión a Internet para cargar los estilos y scripts desde archivos locales.

### Instalación y Uso

1. Clona el repositorio en tu máquina local:

```bash
git clone https://github.com/TemcDesign/cubeDisplay.git
```

2. Navega al directorio del proyecto:

```bash
cd cubedisplay
```

3. Abre el archivo index.html en tu navegador.

### Personalización

CSS: Puedes ajustar las animaciones y estilos en el archivo presentation.css.
JavaScript: Modifica el comportamiento de las animaciones y transiciones en presentation.js.

### Contribuciones

¡Las contribuciones son bienvenidas! Si tienes sugerencias o mejoras, por favor abre un issue o envía un pull request.

### 🔑 Licencia

[MIT](LICENSE.txt) - Creado por [**temcDesign**](https://temcdesign.github.io/portafolio/).
