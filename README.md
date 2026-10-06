🎮 Tres en Raya Pro — Edición Neón
Una versión moderna, elegante y profesional del clásico juego Tres en Raya (Tic-Tac-Toe), construida en una arquitectura de archivo único (Single-File App) para un despliegue ultra rápido en GitHub Pages.
![Tres en Raya Pro Banner](https://img.shields.io/badge/Versi%C3%B3n-1.0.0-00f3ff?style=for-the-badge)
![Licencia](https://img.shields.io/badge/Licencia-MIT-ff007f?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
---
✨ Características Principales
🎨 Interfaz Neón & Glassmorphism: Diseño estilo Cyberpunk/Dark-Slate con neón Cyan (`X`) y Pink (`O`), con efectos visuales de desenfoque e iluminación.
📱 100% Responsivo: Interfaz adaptable a todo tipo de pantallas (Smartphones, Tabletas y Escritorio).
🎛️ Ventana Modal Centrada: Menú de configuración limpio que aparece sobre un fondo difuminado al hacer clic en el botón principal.
🤖 Inteligencia Artificial (Modo Individual):
Fácil: Movimientos aleatorios para una partida casual.
Medio: Una combinación entre lógica táctica y errores humanos.
Imbatible: Desarrollado con el algoritmo de búsqueda Minimax. ¡Es matemáticamente imposible ganarle!
👥 Multijugador Local (Paso a Paso): Desafía a un amigo frente a frente en el mismo dispositivo.
🌐 Multijugador En Línea: Creación y unción a salas privadas mediante códigos de 6 dígitos en tiempo real utilizando Firebase Firestore.
🔊 Efectos de Sonido Sintetizados (Web Audio API): Audio integrado sin necesidad de cargar archivos `.mp3` o recursos externos.
🎆 Efectos Visuales de Victoria: Trazado animado mediante SVG Strike-Through sobre la línea ganadora y lluvia de confeti gracias a `Canvas-Confetti`.
---
🛠️ Tecnologías Utilizadas
Tecnología	Descripción
HTML5 & Vanilla JavaScript (ES6+)	Estructura principal y motor del juego en arquitectura de un solo archivo.
Tailwind CSS (CDN)	Framework de diseño para estilar componentes rápidos e interactivos.
Lucide Icons	Set de iconos vectoriales modernos.
Firebase Cloud Firestore (v11)	Base de datos NoSQL para la sincronización del multijugador en línea.
Web Audio API	Sintetizador de frecuencias para los sonidos del juego.
Canvas Confetti	Efecto de celebración para el ganador.
---
🚀 Despliegue en GitHub Pages
Dado que todo el proyecto está contenido en un único archivo (`index.html`), publicarlo en GitHub Pages toma menos de 2 minutos:
Crea un nuevo repositorio en GitHub:
Nombre sugerido: `tres-en-raya-pro`
Marca la casilla para que sea público.
Sube tus archivos:
Sube el archivo `index.html` y este `README.md` a la rama principal (`main` o `master`).
Activa GitHub Pages:
En tu repositorio de GitHub, ve a Settings (Configuración) > Pages.
En la sección Build and deployment / Source, selecciona `Deploy from a branch`.
Elige la rama `main` (o `master`), carpeta `/ (root)` y haz clic en Save.
Espera unos segundos y obtendrás tu URL pública para compartir y jugar desde cualquier dispositivo:
`https://tu-usuario.github.io/tres-en-raya-pro/`
---
📁 Estructura del Proyecto
```text
├── index.html        # Aplicación completa (HTML, Tailwind, JS, Firebase y Sonidos)
└── README.md         # Documentación del proyecto
```
---
🔧 Configuración del Modo En Línea (Opcional)
Por defecto, la versión incluye una integración lista para conectarse a Firebase SDK. Si deseas conectar el multijugador a tu propio proyecto de Firebase:
Crea un proyecto en Firebase Console.
Habilita Firestore Database y Anonymous Authentication.
Reemplaza las credenciales de Firebase en el script modular al inicio del `index.html`.
---
📝 Licencia
Este proyecto está bajo la Licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente.
---
Desarrollado con HTML, CSS & JavaScript para jugar en cualquier lugar.
