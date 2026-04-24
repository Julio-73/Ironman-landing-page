🚀 Julio Cesar | Landing Page Estilo Iron Man / JARVIS

Ingeniero Full Stack & Especialista en IA — Transformo procesos complejos en soluciones inteligentes, escalables y automatizadas. Más de 5 años construyendo software de alto impacto.

🔥 ¿Qué es este proyecto?
Esta es mi landing page personal profesional, diseñada con una estética futurista inspirada en las interfaces de Tony Stark / JARVIS de Marvel. No es solo una página web: es una experiencia inmersiva que demuestra mis habilidades técnicas avanzadas en frontend, animaciones, WebGL (Three.js) y UX/UI de alto nivel.

✨ Características Principales
✅ Loader Cinematográfico JARVIS: Animación de inicio con reactor arc, barras de progreso, texto tipeado y efectos de flash
✅ Robot 3D Interactivo (Iron Man): Modelo completo creado con Three.js que flota, sigue el mouse y se ensambla/desensambla al hacer clic
✅ Cursor Personalizado: Doble cursor (punto dorado + anillo) con efecto magnético en botones
✅ Efecto de Barrido Cinemático: Transición suave entre secciones al navegar
✅ Barra de Progreso de Scroll: Indicador visual dorado en la parte superior
✅ Animaciones de Revelado: Elementos que aparecen con fade-in + slide-up al hacer scroll
✅ Contadores Animados: Números que incrementan suavemente (5+ años, 20+ proyectos)
✅ Efecto de Tipeo: Texto del hero que se escribe carácter por carácter
✅ Botones Magnéticos: Efecto hover que sigue ligeramente el cursor
✅ Diseño Totalmente Responsive: Adaptado a móvil, tablet y desktop
✅ Glassmorphism + Neumorphism: Tarjetas con efectos de profundidad y transparencia
✅ Partículas 3D: Sparkles dorados, azules y rojos flotando en el fondo
✅ HUD Style: Badges "LIVE · Dashboard Activo" estilo interfaz futurista
✅ Secciones Completas: Hero, Sobre Mí, Servicios, Portafolio, Stack Tecnológico, Testimonios, CTA, Footer

🛠️ Tecnologías Utilizadas

HTML5 Semántico
Estilos
CSS3 Custom Properties (Variables), Flexbox, Grid, Animaciones Keyframes, Glassmorphism, Neumorphism
Interactividad
JavaScript Vanilla (ES6+)
Gráficos 3D
Three.js r128 (WebGL)
Fuentes
Google Fonts: Syne (títulos), DM Sans (cuerpo)
Iconos
SVG inline personalizados
Performance
Lazy loading de imágenes, will-change, transform GPU-accelerated
Accesibilidad
ARIA labels, contraste alto, soporte touch devices
Hosting
GitHub Pages

Tipografía:
Títulos: Syne (Google Fonts) — Bold, moderna, futurista
Cuerpo: DM Sans (Google Fonts) — Legible, limpia, profesional

Inspiración:
🎬 Marvel Cinematic Universe: Interfaces HUD de Iron Man / JARVIS
🖥️ Apple Design Language: Minimalismo funcional
🚀 Linear.app: Microinteracciones y tipografía
🎮 Videojuegos AAA: Efectos de partículas y animaciones fluidas

El modelo de Iron Man tiene 3 estados:

Estado Idle: Flota suavemente, sigue el movimiento del mouse, ojos brillan en cyan
Click → Desensamblaje: Las piezas vuelan en direcciones aleatorias con rotación y escala reducida
Click → Reensamblaje: Las piezas regresan desde posiciones lejanas con efecto de arco y shake final + flash rojo/azul
Detalles Técnicos del Robot
~80 piezas individuales creadas con geometrías básicas de Three.js (Box, Sphere, Cylinder, Torus)
Materiales PBR: MeshPhysicalMaterial con metalness, roughness, clearcoat, transmission
Iluminación avanzada: Ambient + Directional (key, fill, rim) + Point lights (arc reactor, underglow) + SpotLight para sombras
Partículas: 3 sistemas de puntos (cyan, gold, red) con blending aditivo
Raycaster: Detección de clicks en el detector invisible del pecho
Animaciones: Ease-in cubic (desensamblaje), ease-out cubic (reensamblaje), sine waves (floating idle)
Efectos post-click: Camera shake, flash radial, ojos rojos temporales, anillo expansivo cyan
📱 Responsive Design
Breakpoint
Comportamiento
> 1000px
Layout completo, cursor personalizado activo, nav horizontal
≤ 1000px
Menú hamburguesa, grid de servicios/portafolio en 1 columna, hero en stack vertical
≤ 600px
Padding reducido, stats en wrap, tech grid en 4 columnas, botones apilados
📲 Touch Devices: El cursor personalizado se oculta automáticamente en dispositivos táctiles (hover: none media query).

🧪 Performance Optimizations:
✅ Lazy Loading: Imágenes del portafolio con loading="lazy"
✅ GPU Acceleration: Uso de transform y opacity para animaciones (evita layout thrashing)
✅ Will-Change: Aplicado estratégicamente en elementos animados
✅ RequestAnimationFrame: Loop de animación optimizado para 60fps
✅ Intersection Observer: Revelado de elementos solo cuando entran en viewport
✅ CDN para Three.js: Carga rápida desde Cloudflare CDN
✅ Single File: Sin requests HTTP adicionales (excepto fuentes e imágenes)
🤝 Contribuciones

📄 Licencia:
Este proyecto es de uso personal y profesional. No se permite su redistribución comercial sin permiso explícito.
© 2026 Julio Cesar Quispe Garrido. Todos los derechos reservados.

📬 Contacto:

¿Te gustó el proyecto? ¿Quieres colaborar o contratarme?

📩 Email: julioquispe.dev@gmail.com
💼 LinkedIn: https://www.linkedin.com/in/julio-cesar-quispe-garrido/
📂 GitHub: https://github.com/Julio-73
🌐 Portfolio: https://julio-73.github.io/Ironman-landing-page/
