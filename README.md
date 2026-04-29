# Restaurante Sabores de Chile - Prototipo Web v6.0

Este proyecto corresponde a la tarea de la **Semana 6** de la asignatura **Programación Web I**. En esta etapa, el foco principal es la aplicación del **Modelo de Cajas (Box Model)**, técnicas de **Posicionamiento** y el **Dimensionamiento** avanzado de elementos para lograr una maquetación profesional.

## 📝 Descripción del Proyecto

En esta versión se transformó la estructura visual del sitio mediante el control del espacio y la ubicación de los elementos:

### 1. Aplicación del Modelo de Cajas (Box Model)
Se configuraron las secciones principales (`header`, `main`, `footer`) controlando sus cuatro componentes esenciales:
- **Contenido:** Definición de dimensiones mediante `width` y `height`.
- **Relleno (Padding):** Generación de espacio interno para mejorar la legibilidad y evitar que el contenido toque los bordes.
- **Borde (Border):** Implementación de bordes decorativos y funcionales para delimitar las áreas de navegación y menú.
- **Margen (Margin):** Control de la separación externa entre secciones y centrado horizontal de la caja principal mediante `margin: auto`.

### 2. Estética y Legibilidad del Menú
Se optimizaron los elementos de datos para facilitar la comprensión de la oferta gastronómica:
- **Tablas de Menú:** Uso de `border-collapse` y `box-shadow` para crear una presentación limpia y con profundidad visual.
- **Listas de Promociones:** Transformación de la lista mediante `list-style: none` y el uso de bordes laterales destacados para jerarquizar las ofertas especiales.
- **Tipografía:** Cambio de fuentes y ajuste de tamaños de texto para mejorar la estética general y reducir la fatiga visual.

### 3. Posicionamiento y Dimensionamiento Multimedia
Se aplicaron técnicas de posicionamiento avanzado en la sección "Plato de la Semana" para lograr una disposición atractiva de las imágenes:
- **Posicionamiento Relativo (`relative`):** Utilizado como marco de referencia para elementos hijos.
- **Posicionamiento Absoluto (`absolute`):** Implementación de etiquetas decorativas ("¡Lo más pedido!") superpuestas a las imágenes, rompiendo el flujo normal del documento.
- **Dimensionamiento:** Uso de `max-width` y `height: auto` para asegurar que los elementos multimedia mantengan su proporción y se adapten al contenedor padre.

## 🛠️ Tecnologías Utilizadas
- **HTML5:** Estructura semántica, formularios y multimedia.
- **CSS3:** Modelo de cajas, posicionamiento (relative/absolute), dimensionamiento y efectos visuales (sombras, transiciones).
- **Navegador Recomendado:** Google Chrome (por su alto cumplimiento de estándares CSS3).

## 👩‍💻 Desarrollado por:

* Tamara Muñoz Zamora