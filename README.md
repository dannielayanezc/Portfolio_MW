# Portafolio Nebulosa · Daniela Yañez

**Autora:** María Fernanda Daniela Yañez Cruz (Daniela Yañez) · Diseñadora Gráfica · Universidad La Salle

Portafolio digital con identidad de nebulosa: una galaxia fija que cambia de colores análogos al recorrer la página y con cada proyecto, estrellas tenues, cápsulas de proyecto y un kit de herramientas en órbita alrededor de mi conejito.

## Sitio publicado

https://dannielayanezc.github.io/Portfolio_MW/

## Contenido del repositorio

| Archivo | Qué es |
|---|---|
| `index.html` | Estructura del portafolio. |
| `css/styles.css` | Sistema de diseño en variables CSS (color, tipografía, espaciado, profundidad), clases reutilizables y estilos responsivos. |
| `css/galaxia.css` | Máscaras de la galaxia (vertical y horizontal) incrustadas para que funcione también al abrir el archivo directo. |
| `js/main.js` | Galaxia y estrellas, navegación y menú móvil, órbita de herramientas, cápsulas con filtros y línea deslizable, desglose de proyectos, visor de imágenes con gestos y zoom, vistas 360° y formulario. |
| `assets/img/` | Foto, conejito, logotipos e imágenes de los proyectos. |
| `assets/giro/` | Secuencias de las vistas 360° de los envases de Baygon. |

Hecho con HTML, CSS y JavaScript, sin librerías externas. Tipografías: Gunter (Adobe Fonts) y Plus Jakarta Sans (Google Fonts).

## Proyectos

Estrellas Variables · Baygon · FICM · Kleenex Winter · Libro Azul · Femme Fatale · Sushi Roll

## Cómo verlo localmente

Abre `index.html` en el navegador, o levanta un servidor local con `python3 -m http.server 8765` y entra a `http://localhost:8765/`.

## Accesibilidad

- Navegación con teclado, incluido el visor de imágenes (← → y Esc).
- Foco visible y enlace **Saltar al contenido**.
- Texto blanco sobre la galaxia, con contraste legible.
- Respeta **reducir movimiento**: la galaxia, la órbita y los destellos se detienen.
- Áreas táctiles de mínimo 48 × 48 px en móvil.
