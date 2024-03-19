# Powerlifting Blog

## Descripción

Este proyecto es un blog dedicado al mundo del powerlifting, construido utilizando React. El blog presenta características como la visualización de posts, manejo de estados de carga y error, y un diseño responsivo. Los usuarios pueden leer sobre competiciones, técnicas de entrenamiento, y consejos de nutrición específicos para powerlifters.

## Tecnologías Utilizadas

- HTML5
- React.js
- Prop-types para la validación de propiedades en componentes React
- Fetch API para la comunicación con una API externa

## Instalación

Este proyecto se ejecuta directamente en el navegador y no requiere instalación de dependencias adicionales gracias al uso de CDN para React, ReactDOM, Babel y PropTypes. Para utilizar este proyecto, simplemente copia el código HTML en un archivo `.html` y ábrelo con tu navegador.

## Uso

1. **Visualización de Posts**: Al cargar el blog, los posts se cargan automáticamente desde una API externa y se muestran al usuario.
2. **Manejo de Estados**: El blog maneja varios estados de la interfaz, incluyendo la carga de datos, el estado vacío cuando no hay posts disponibles, y errores de comunicación con la API.
3. **Responsivo**: El diseño del blog es responsivo, adaptándose a diferentes tamaños de pantalla para una óptima visualización en dispositivos móviles y de escritorio.

## Características

- **Header y Footer**: Componentes que muestran información constante.
- **Card**: Componente que muestra la información de cada post, incluyendo título, contenido, y detalles del competidor.
- **Manejo de Errores y Estado Vacío**: El blog detecta y notifica al usuario si ocurre un error durante la carga de los posts o si no hay posts para mostrar.

## Créditos

Desarrollado por Esteban Zambrano 2024. Derechos de autor de la Universidad del Valle de Guatemala (UVG).

## Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.
