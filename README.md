# Mi Portfolio Personal (v1) 🚀

[![Astro](https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

Bienvenido al repositorio de mi portfolio personal. Este proyecto es una presentación interactiva de mi trabajo, habilidades y experiencia, diseñado con un enfoque en el rendimiento, la estética minimalista y la experiencia de usuario.

*🔗 [Visita mi portfolio en vivo (Demo)](https://portfoliov1-tatapierce.vercel.app/)*

## 🛠️ Tecnologías Utilizadas

Este proyecto fue construido utilizando tecnologías web modernas para asegurar un alto rendimiento y mantenibilidad:

- **[Astro](https://astro.build/):** Framework web utilizado como base. Se eligió por su arquitectura de "Islas" y su capacidad de generar sitios estáticos ultrarrápidos sin enviar JavaScript innecesario al cliente (Zero JS by default).
- **[Tailwind CSS v4](https://tailwindcss.com/):** Framework de CSS utilitario utilizado para estilizar todo el sitio de manera rápida, responsiva y manteniendo un sistema de diseño consistente.
- **HTML5 & Vanilla JavaScript:** Para la estructura semántica y la lógica de interacciones específicas (como el efecto de partículas en el fondo).

## 🧠 Planificación y Arquitectura del Proyecto

El desarrollo de este portfolio siguió una metodología de migración y optimización estructurada:

1. **Diseño y Estructura Inicial (HTML/CSS Base):** El proyecto comenzó como una estructura sólida en HTML puro.
2. **Migración a Astro:** Para mejorar la mantenibilidad y el rendimiento a largo plazo, el código estático se refactorizó utilizando el sistema de componentes de Astro (`.astro`). Esto permitió dividir el diseño en piezas reutilizables (Navbar, Hero, Proyectos, Footer, etc.).
3. **Integración de Tailwind CSS:** Se reemplazó el CSS tradicional por Tailwind CSS v4. Esto unificó los tokens de diseño, garantizó un espaciado consistente y facilitó la creación de un modo oscuro y diseños adaptables (responsive).
4. **Optimización de Layout y Estética:** Se hizo un fuerte énfasis en reducir el espaciado vertical innecesario para lograr un flujo de lectura continuo y profesional. Se implementaron efectos sutiles como "glassmorphism" (superficies translúcidas) y un fondo dinámico de partículas.

## ✨ Características Principales

- **Rendimiento Extremo:** Gracias a Astro, el sitio carga casi instantáneamente.
- **Diseño Responsive:** Totalmente adaptable a dispositivos móviles, tablets y monitores de escritorio.
- **Estética Minimalista y Moderna:** Uso cuidadoso de tipografía, colores armoniosos y efectos de superposición.
- **Efecto de Partículas Interactivos:** Fondo dinámico que añade un toque tecnológico y vivo sin comprometer el rendimiento.

## 🚀 Instalación y Desarrollo Local

Si deseas clonar y ejecutar este proyecto en tu máquina local, sigue estos pasos:

### Prerrequisitos

- [Node.js](https://nodejs.org/) (Versión 22.12.0 o superior)

### Pasos

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/portfolio-v1.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd portfolio-v1
   ```
3. Instala las dependencias:
   ```bash
   npm install
   ```
4. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```
5. Abre tu navegador en `http://localhost:4321` para ver el resultado.

---

*Diseñado y desarrollado con ☕ y 💻.*