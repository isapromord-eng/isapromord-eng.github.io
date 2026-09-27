# 🧠 MEMORY.md — Bitácora Histórica y Aprendizajes de IsaPromo RD

> **Regla Sagrada:** Este archivo es **APPEND-ONLY**. Jamás borrar registros anteriores. Cada entrada debe incluir fecha en formato `[YYYY-MM-DD]`.

---

## [2026-09-27] - Inicialización Oficial de IsaPromo RD (isapromord.com) & Arquitectura SEO Local

### 1. Contexto & Diagnóstico Previo
- El dominio `isapromord.com` y los deployments anteriores en Netlify estaban inactivos debido a la cancelación de la cuenta externa.
- Se decidió reiniciar y reconstruir el sitio web insignia de la agencia con un estándar de ingeniería de alto nivel y un enfoque radical en **SEO Local para República Dominicana**, preparado para indexación en Google Search Console y sincronización con Google Business Profile.

### 2. Decisiones Técnicas y de Diseño
- **Estilo Visual:** Se adoptó la estética *Clean Modern Agency* (fondo off-white/luminoso, tarjetas con sombras suaves, espacios amplios y acentos vibrantes inspirados en el logo 3D oficial).
- **SEO Técnico:**
  - Inyección de datos estructurados JSON-LD (`LocalBusiness`, `ProfessionalService`, `FAQPage`, `Service`).
  - Implementación de Geo-Metatags (`geo.region: DO-01`, `geo.placename: Santo Domingo`, coordenadas GPS de RD).
  - Open Graph y Twitter Cards completos con imagen representativa.
  - Creación de `robots.txt` y `sitemap.xml` canónicos para rastreo óptimo de Googlebot.
  - Conversión optimizada con click-to-WhatsApp pre-configurado y widget interactivo de auditoría SEO local.

### 3. Activos Vinculados
- Logotipo oficial 3D ubicado en `assets/logo.png`.
- Repositorio conectado a la organización matriz `isapromord-eng`.

## [2026-09-27] - Despliegue de Arquitectura Base e Inicialización de Control de Versiones
- **Archivos Nucleares Generados:**
  - `index.html`: Estructura semántica completa con microdatos Schema.org, Geo-metatags dominicanos, simulador interactivo de visibilidad en Google Maps, cuadrícula de servicios, acordeón FAQ y botón flotante de WhatsApp.
  - `robots.txt`: Directivas específicas para Googlebot y Bingbot con referencia a `sitemap.xml`.
  - `sitemap.xml`: Mapa del sitio XML canónico con metadatos de imagen para indexación prioritaria.
  - `.mbos/HANDOFF.md`: Hoja de ruta para conexión DNS y Google Search Console.
- **Control de Versiones:** Repositorio Git local inicializado con commit raíz `87ef012`.

## [2026-09-27] - Transformación UX/UI Grado Agencia Mundial (Anti-Template Overhaul)
- **Crítica de Diseño Atendida:** Se eliminó la apariencia de "plantilla genérica de IA".
- **Nuevos Módulos Interactivos de Alta Conversión:**
  - **Simulador SERP y Google Maps 3D:** Barra de búsqueda animada con efecto typing dinámico alternando las palabras clave de compra en RD, junto a un mapa visual con pines de ranking (#1 Piantini, #1 Naco, #1 Santiago) y comparativa directa frente a competidores.
  - **Bento Grid Asimétrico:** Módulos de Geo-Grid 360°, velocímetro Core Web Vitals 100/100, simulación de chat WhatsApp directo y visor de código Schema JSON-LD.
  - **Live Activity Toast:** Notificador flotante en tiempo real que simula empresas locales subiendo de posición en Google Maps.
  - **Marquee Infinito:** Carrusel continuo con marcas locales dominicanas.
  - **Escáner Interactivo con Barra de Progreso:** Animación de carga y cálculo de llamadas perdidas con entrega de reporte directo a WhatsApp.

## [2026-09-27] - Actualización de Identidad Visual 3D (Versión 2 Oficial)
- **Selección de Marca:** El usuario seleccionó la Versión 2 de alta fidelidad 3D (Claymorphic / Fluent 3D) con barra de Google Search, megáfono dorado en relieve, diana de tiro al blanco afilada y avatares hexagonales translúcidos.
- **Acción Técnica:** Se reemplazó `assets/logo.png` con la nueva versión renderizada y se respaldó la anterior en `assets/logo_legacy.png`.
- **Despliegue:** Sincronizado a través de Git y publicado automáticamente en GitHub Pages.



