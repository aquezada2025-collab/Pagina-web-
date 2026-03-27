# Gestión de Imágenes con CSS

## Descripción General
La página presenta un recorrido por la industria de los videojuegos, destacando empresas líderes y títulos icónicos. El objetivo principal de esta entrega fue demostrar el dominio de la propiedad de caja y el control de elementos multimedia (imágenes) a través de CSS.

## 🖼️Gestión de Imágenes mediante CSS

Siguiendo las instrucciones de la actividad, toda la estilización y el dimensionamiento de las imágenes se realizó de forma **externa** en el archivo `style.css`. Se aplicaron las siguientes acciones correctivas y evolutivas:

### 1. Dimensionamiento Diferenciado (Requisito Principal)
Cada sección de imágenes fue gestionada con selectores específicos para asegurar que **todas las imágenes tengan tamaños distintos**, optimizando su visualización según su importancia en el contenido:
* **Sección Principal (`.imagenes_1`):** Se utilizaron porcentajes dinámicos (49% y 45%) para crear una composición asimétrica y fluida.
* **Sección Secundaria (`.imagenes_2`):** Se definió un ancho de 460px para equilibrar las imágenes con los encabezados de texto.
* **Imagen Destacada (`.imagenes_3`):** Se asignó un tamaño de gran formato (900px) con centrado automático (`margin: 0 auto`) para jerarquizar el contenido visual.
* **Galería Final (`.imagenes_4`):** Se ajustó a un ancho de 510px para complementar el diseño de flexbox.

### 2. Estilización Evolutiva
Además del tamaño, se añadieron propiedades para mejorar la estética:
* **Border Radius:** Se aplicaron bordes redondeados para suavizar la integración de las fotos con el fondo claro de los artículos.
* **Layout Flexbox:** Se utilizaron contenedores con `display: flex`, `gap` y `align-items` para garantizar que las imágenes y los textos estén perfectamente alineados sin depender de atributos HTML antiguos.
* **Proporcionalidad:** Se utilizó `height: auto` en todos los selectores para prevenir la distorsión de las imágenes y mantener su relación de aspecto original.

## Tecnologías Utilizadas
* **HTML5:** Estructura semántica del sitio.
* **CSS3:** Gestión de diseño, posicionamiento `sticky` para el menú, y control total de dimensiones de imágenes.
