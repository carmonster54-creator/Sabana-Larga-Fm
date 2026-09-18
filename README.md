# 📻 Sabana Larga FM V16 - Póster Web Interactivo

Este proyecto es un **póster promocional interactivo** desarrollado como una página web. Está diseñado para promocionar la emisora **Sabana Larga FM V16**, permitiendo a los usuarios escuchar la radio en vivo y descargar la aplicación oficial directamente desde sus dispositivos móviles.

## ✨ Características Principales

*   **🎧 Reproductor en Vivo:** Integración de un reproductor de audio que conecta directamente con el stream de la emisora (`listen2myradio`). El botón cambia de "Play" a "Pausa" dinámicamente.
*   **📱 Enlaces a Google Play:** Botones y códigos QR que redirigen directamente a la página de descarga de la aplicación oficial en Google Play Store.
*   **🎨 Diseño Visual Atractivo:** Interfaz con temática caribeña, utilizando una imagen de fondo de un estudio de televisión y un logotipo personalizado.
*   **📱 Diseño Responsivo (Mobile-First):** La página se adapta automáticamente al tamaño de la pantalla. En computadoras se ve como un póster de dos columnas, y en celulares se apila verticalmente para facilitar la lectura.
*   **🔗 Enlace Compartible:** Listo para ser alojado en servicios de hosting estático (como Netlify, Vercel o GitHub Pages) para ser compartido mediante una URL.

## 🛠️ Tecnologías Utilizadas

*   **HTML5:** Estructura semántica del póster.
*   **CSS3:** Estilos avanzados (Flexbox, Grid, gradientes, efectos de desenfoque `backdrop-filter` y animaciones).
*   **JavaScript (Vanilla):** Lógica para controlar la reproducción del stream de audio en vivo.
*   **Google Fonts:** Tipografías *Montserrat* y *Oswald* para un diseño moderno.

## 📂 Estructura del Proyecto

Para que el póster funcione correctamente, asegúrate de que los siguientes archivos estén en la misma carpeta:

```text
/
├── index.html (o poster.html)  # El código principal del póster
├── logo.png                    # Logotipo de Sabana Larga FM V16
└── fondo.jpg                   # Imagen de fondo (estudio de TV)
