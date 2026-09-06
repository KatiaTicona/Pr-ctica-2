# Katia Ticona — Perfil Académico & Portafolio Web

Este repositorio contiene el código fuente de mi página web personal y portafolio académico. Es un sitio web de una sola página (*single-page layout*), ligero, accesible y adaptable, diseñado para destacar mi formación académica, publicaciones y trayectoria en el área de Ingeniería Estadística e Informática y la Gerencia de TIC.

---

## 🌟 Características

- **Diseño Moderno y Estilizado:**
  - Paleta de colores suaves en tonos lila, rosa y tinta.
  - Efectos de fondo flotantes (*ambient gradient blobs*) mediante animaciones CSS.
  - Resplandor interactivo (*cursor glow*) que sigue el movimiento del puntero.
- **Interactividad & UX:**
  - Barra de progreso de lectura (*scroll progress bar*).
  - Menú de navegación pegajoso (*sticky topnav*) con espía de desplazamiento (*scroll spy*).
  - Tarjetas interactivas con efecto giratorio (*flip cards*) para resúmenes de publicaciones científicas.
  - Botón de un solo clic para copiar la dirección de correo al portapapeles.
  - Contadores numéricos animados para estadísticas.
- **Mini-Juego Incluido:** Un clásico juego de *Snake* integrado en canvas con soporte para teclado y pad táctil.
- **Accesibilidad y Rendimiento:**
  - Soporte para la preferencia de movimiento reducido (`prefers-reduced-motion`).
  - Totalmente adaptativo (*responsive*) para dispositivos móviles y de escritorio.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructura semántica de la página.
- **CSS3:** Estilos personalizados, Flexbox, Grid, variables CSS, animaciones nativas y diseño adaptable sin librerías externas.
- **JavaScript (ES6+):** Manipulación del DOM, Web APIs (`IntersectionObserver`, `Clipboard API`, `Canvas API`) y la lógica del mini-juego.
- **Google Fonts:**
  - *Fraunces* (Títulos y acentos)
  - *Poppins* (Cuerpo de texto)
  - *IBM Plex Mono* (Etiquetas y código)

---

## 📂 Estructura del Proyecto

```text
.
├── index.html        # Documento principal con la estructura, estilos e interactividad
└── README.md         # Documentación del repositorio
