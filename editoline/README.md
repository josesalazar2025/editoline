
## EDITOLINE

Proyecto web responsive desarrollado como ejercicio de maquetación avanzada utilizando HTML y CSS moderno.

---

## Descripción

EDITOLINE es una web responsive construida desde cero aplicando técnicas avanzadas de CSS como:

- Layout con Grid y Flexbox
- Tipografía fluida con clamp()
- Transiciones y transformaciones
- Scroll Snap
- Estados interactivos (hover, focus)
- Enfoque Mobile First

---

El objetivo del proyecto es consolidar la capacidad de maquetación profesional sin el uso de JavaScript.


Apostamos por una identidad de marca con corte alternativo que ofrece una plataforma de distribución de ilustraciones y narrativas gráficas para artistas independientes, siendo este su 
principal factor diferenciador. 

---

## Objetivos del proyecto

- Construir una web completamente responsive.
- Aplicar buenas prácticas de estructura HTML semántica.
- Utilizar CSS moderno para crear layouts complejos.
- Implementar microinteracciones visuales.
- Mantener un código limpio y organizado.

---

## Tecnologías utilizadas

- HTML5 (semántico)
- CSS3
  - Flexbox
  - CSS Grid
  - clamp()
  - Scroll Snap
  - Transiciones
  - Transformaciones
- Git y GitHub 

---

## 📂 Estructura del proyecto

/editoline
├── index.html
├── catalogo.html
├── noticias.html
├── talent.html
├── contacto.html
├── css/
│ └── styles.css
├── assets/
│ ├── images/
│ └── video/
└── README.md

---

Breve explicación de la organización:

- `index.html`: introducción al concepto de la editorial y los artículos más vendidos y en tendencia.
- `catalogo.html` : categorías de las revistas y una descripción más amplia de cada una. 
- `noticias.html`: articulos de prensa online relevantes para el concepto de la editorial.
- `talent.html` : pensada en reseñar brevemente a los artistas que participan con sus proyects en la editorial.
- `contacto.html`: formulario para enviar propuestas artísticas y mapa con la dirección de las oficinas del CIFO-La Violeta.
- `css/`: hojas de estilo.
- `assets/`: recursos estáticos.

---

## Responsive Design

El proyecto está desarrollado con enfoque **Mobile First**.

Breakpoints utilizados:

- Mobile: diseño base.
- Tablet: ajustes de layout.
- Desktop: distribución avanzada con Grid.

Se han utilizado unidades relativas (`rem`, `%`, `vw`) y tipografía fluida mediante `clamp()` para garantizar escalabilidad.

---

## Decisiones técnicas relevantes
- Decidimos utilizar GitHub desde el inicio para contar con el control de versiones y poder trabajar comodamente con los aportes de cada uno.
- Escogimos grid para el layout del body por su versatilidad y facilidad de implementación ese contexto, nos permite ajustar los tamaños
deseados para cada uno de los componentes y facilita el diseño responsive.
- Para el menún de navegación optamos por un sticky nav en la parte superior del body con enlaces con aria-label (para marcar el sitio activo) y el nombre de la editorial.
- Se aplica la técnica del checkbox oculto para el hamburguer menu que se activa durante las vistas tablet y móvil.
- Para el header se decide aprovecharlo para las revistas destacadas de la editorial (hero). Se implementa el scroll bar horizontal con snap
al principio de cada imagen y se le dan estilos (incluyendo a Firefox).
- Para el layout del main se opta por utilizar flex, tanto en sus contenedores como en sus tarjetas para mayor control y separación visual de cada
sección.
- El uso de transiciones, transformaciones, hover/focus está bastante controlado y limitado a elementos que lo ameriten y que enriquecieran la experiencia de usuario.
- Tratamos de mantener presente la accesibilidad/usabilidad en todo momento y se hicieron varias correcciones de contraste/tamaño de tipografías a lo largo del proyecto, se implementaron 
textos alternativos para los lectores de pantalla, se mantuvo una separación adecuada entre los elementos y secciones, además de un diseño consistente entre todas las páginas de la web.

## Retos encontrados

José:

Entorno colaborativo:
Al ser la segunda vez que trabajo con GitHub de forma colaborativa, el inicio del proyecto fué un poco desordenado y resultaba en 
conflictos frecuentes en los PR de cada uno. 
La solución fué dedicarle más tiempo a la fase de planificación y unificación de criterios, además de repasar un poco el uso de GitHub en la
terminal, lo cual me permitió consolidar conocimientos previos.

Layout en el footer:
Estabamos ya habituados a hacer un footer con simplemente el autor y copyright y optamos por un diseño más completo.
Hacer que los elementos adoptaran la ubicación deseada y fluyeran con responsive adecuado requirió de varios intentos con grid/flex.

Mejoré mucho las habilidades de uso de flex/grid y de las tipografias fluidas, además de aclarar algunas etiquetas de html cuyo uso lo tenía confundido.
Aprendí como hacer los análisis de Lighthouse con developer tools de Google Chrome.

Mary:
Durante la creación de la estructura de la página mi mayor reto fue ajustar las tarjetas y su contenido, ya que dependiendo de cada página, 
el contenido de cada main varía pero todas la páginas debían mantener una estructura y estética común. Además había que tener el cuenta el responsive y controlar los ajustes dependiento 
del tamaño de la pantalla sin sacrificar el aspecto informativo o comercial de la página.

Gracias a ello aprendí como se crea una buena base para el HTML, el uso correcto de Github para mantener mi trabajo y el del compañero al día a pesar de los cambios. 
Como priorizar ciertas líneas de código, el uso correcto de selectores dependiendo del main donde se trabajaba, que también ayudaba a no pisar el trabajo del compañero.


## Mejoras futuras

Ejemplos:

- Header con slideshow automático
- Botones de like accionables.
- Implementación de un carrito de compra.
- Páginas de detalles para cada revista con descripción completa.
- Sección de subscripción.
- Adjuntar archivos para el formulario.
- Barra de búsqueda.
- Ampliar categorías.
- Optimización de rendimiento ya que el sitio hace uso de muchas imagenes y poco texto.
- Mejora de accesibilidad.


## Demo

Enlace a GitHub Pages / Vercel / Netlify (si está desplegado).

---

- HTML validado con W3C ✔
- CSS validado ✔
- Lighthouse Performance: 89
- Lighthouse Accessibility: 94
- Lighthouse SEO: 100
- Lighthouse Best Practices: 100



## Autores
José Salazar
Mary Ramos (Nzinga Mbande)

Curso de confección y publicación de páginas web CIFO-La Violeta
Barcelona, 2026

---



## USO RESPONSABLE DE IA:

**PROMPT-CHAT GPT:**

Una plataforma pensada en ofrecer espacios de visibilidad a artistas nuevos y emergentes en donde encontrarás un curaduría basada en originalidad e itención, además de impulsar géneros opacados por las tendencias convencionales. 

Corrige la redaccion y amplia las ideas. Se trata de una editorial de revistas ilustradas como comics, manga enfocada en talento under.

**RESPUESTA:**

Va, te dejo una introducción más amplia y cuidada, con un tono editorial y cultural, ideal para una editorial independiente:

> Somos una editorial de revistas ilustradas dedicada al impulso de talento under, nuevos y emergentes, con un enfoque especial en el cómic, el manga y las narrativas gráficas contemporáneas. Nacemos como una plataforma pensada para ofrecer espacios reales de visibilidad a artistas que crean desde los márgenes, apostando por propuestas auténticas y arriesgadas.
>
> Nuestra curaduría se basa en la originalidad, la intención y la fuerza del discurso visual, priorizando obras que se alejan de las fórmulas dominantes y de las tendencias convencionales. Buscamos amplificar géneros, estilos y voces que suelen quedar opacados, construyendo un catálogo diverso que dialogue con la ilustración, la narrativa gráfica y la experimentación artística.
>

**PRONT-CLAUDE SONNET 4.5**

Explain in detail how to apply CSS hamburguer button trick with pure CSS

RESPUESTA:

<nav class="navbar">
  <!-- Hidden checkbox that controls everything -->
  <input type="checkbox" id="menu-toggle" class="menu-toggle">
  
  <!-- The hamburger icon (label acts as the clickable button) -->
  <label for="menu-toggle" class="hamburger">
    <span class="bar"></span>
    <span class="bar"></span>
    <span class="bar"></span>
  </label>
  
  <!-- The navigation menu -->
  <ul class="menu">
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#services">Services</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>
/* Hide the checkbox completely */
.menu-toggle {
  display: none;
}

/* Style the hamburger container */
.hamburger {
  display: none; /* Hidden on desktop */
  cursor: pointer;
  flex-direction: column;
  gap: 5px;
  padding: 10px;
  z-index: 1000;
}

/* The three bars of the hamburger */
.bar {
  width: 25px;
  height: 3px;
  background-color: #333;
  transition: all 0.3s ease;
  border-radius: 3px;
}

/* Desktop menu styling */
.menu {
  display: flex;
  gap: 20px;
  list-style: none;
  margin: 0;
  padding: 0;
}

/* Mobile styles */
@media (max-width: 768px) {
  .hamburger {
    display: flex; /* Show hamburger on mobile */
  }
  
  /* Hide menu by default on mobile */
  .menu {
    position: fixed;
    top: 0;
    right: -100%; /* Off-screen */
    height: 100vh;
    width: 250px;
    flex-direction: column;
    background-color: white;
    box-shadow: -2px 0 5px rgba(0,0,0,0.1);
    padding: 60px 20px 20px;
    transition: right 0.3s ease;
  }
  
  /* THE KEY TRICK: When checkbox is checked, slide menu in */
  .menu-toggle:checked ~ .menu {
    right: 0;
  }
  
  /* Transform hamburger into X when checked */
  .menu-toggle:checked ~ .hamburger .bar:nth-child(1) {
    transform: rotate(45deg) translate(7px, 7px);
  }
  
  .menu-toggle:checked ~ .hamburger .bar:nth-child(2) {
    opacity: 0; /* Hide middle bar */
  }
  
  .menu-toggle:checked ~ .hamburger .bar:nth-child(3) {
    transform: rotate(-45deg) translate(7px, -7px);
  }

}

How It Works

The Checkbox: A hidden <input type="checkbox"> serves as the state manager. When checked, it changes the state without JavaScript.
The Label: The <label for="menu-toggle"> is connected to the checkbox through the for attribute. Clicking the label toggles the checkbox.
The Sibling Selector: The ~ (general sibling combinator) allows you to target elements that come after the checkbox in the DOM when it's checked: .menu-toggle:checked ~ .menu
The Animation: CSS transitions smooth the transformation of both the menu position and the hamburger icon.

Key Advantages

No JavaScript required - purely declarative CSS
Accessible - uses native checkbox semantics
Performant - CSS transitions are hardware-accelerated
SEO-friendly - content is in the HTML, just hidden visually

Alternative Patterns
You can also create variations like:
Overlay background:

.menu-toggle:checked ~ .menu::before {
  content: '';
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.5);
  z-index: -1;
}

Slide from left:
.menu {
  left: -100%; /* Instead of right */
}

.menu-toggle:checked ~ .menu {
  left: 0;
}
This technique is elegant because it leverages CSS's ability to respond to element states without requiring any scripting, making it lightweight and maintainable for simple navigation scenarios.