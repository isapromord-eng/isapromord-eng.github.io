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

## [2026-09-27] - Integración de Estrategia de Doble Pilar (Páginas Web + SEO Local)
- **Alineación Comercial:** Se equilibró la propuesta de valor para no encasillar a IsaPromo RD únicamente en SEO Local. Ahora se posiciona con igual fuerza como estudio de **Diseño y Desarrollo de Páginas Web de Alta Conversión (<1s de carga)** y **Posicionamiento en Google Maps**, facilitando el bucle de ventas cruzadas (upsell).
- **Componentes Visuales Nuevos:**
  - Selector interactivo de dos pestañas en el Hero: `⚡ 1. Páginas Web (<1s)` vs `📍 2. Google Maps (#1)`.
  - Módulo de comparativa visual: "Web Tradicional en RD (5.8s, 0 ventas)" vs "Ingeniería IsaPromo RD (100 Core Web Vitals, WhatsApp directo)".
  - Actualización del grafo Schema.org JSON-LD para registrar ambos servicios formalmente ante Google.

## [2026-09-27] - Evolución Tipográfica de Marca: ISAPromoRD (Opción A - Color Dividido)
- **Decisión de Identidad:** Tras análisis de legibilidad fonética y de jerarquía visual, se seleccionó oficialmente el formato de capitulación **ISAPromoRD**.
- **Tratamiento Tipográfico (Opción A):**
  - `ISA`: En negro sólido / slate-950 (connotación de acrónimo institucional / tecnológico).
  - `Promo`: En gris oscuro / slate-700 (palabra comercial en formato título legible).
  - `RD`: En azul eléctrico de marca / brand-600 (anclaje geográfico de República Dominicana).
- **Sincronización:** Se actualizó en `index.html`, metadatos, Schema.org JSON-LD, `BRAIN.md` y enlaces de llamada a la acción de WhatsApp.

## [2026-09-27] - Remoción de 'Digital Lab' y Estandarización de Tipografía Móvil (Google & Apple HIG)
- **Eliminación de Badge:** Se retiró la etiqueta genérica `DIGITAL LAB` de la barra de navegación para una apariencia más limpia, corporativa y despejada.
- **Auditoría de Tamaños de Fuente Móviles:**
  - El sitio contenía clases microscópicas heredadas (`text-[10px]`, `text-[11px]`) que afectaban la legibilidad en pantallas móviles y violaban las directrices de usabilidad de Google (*"Text too small to read"*).
  - Se eliminaron por completo todas las instancias de fuentes inferiores a 12px.
  - Se estandarizó el cuerpo de texto a 15-16px (`text-base` y `text-sm sm:text-base`).
  - Las microcopias, etiquetas, chips y datos secundarios se elevaron a 12-14px (`text-xs sm:text-sm font-semibold` o `font-bold`).
  - Los campos de entrada (`<input>`, `<select>`) se fijaron en 16px (`text-base`) para evitar el molesto auto-zoom de iOS Safari en iPhones al tocar los formularios.
  - Los títulos de tarjetas, acordeón FAQ y botones de acción se ampliaron para cumplir los estándares de áreas de toque ergonómicas (mínimo 48px).

## [2026-09-27] - Corrección de Percepción Visual Móvil: Eliminación de Padding Anidado y Despeje de Viewport
- **Diagnóstico del Efecto "Muñeca Rusa" (Russian Doll):**
  - Aunque los textos ya estaban en 14-16px, la percepción en móvil seguía viéndose diminuta. La causa raíz fue la acumulación de 4 capas de paddings anidados (`px-4` + `p-6` + `p-6` + `p-5`), reduciendo el ancho utilizable a escasos 220px y forzando saltos de línea cada 2 palabras (apariencia de maqueta en miniatura).
- **Acciones Correctivas de Grado Industria:**
  - Reducción de paddings envolventes en móvil a `p-3.5 sm:p-8`, recuperando más de 50px de espacio útil en la pantalla del teléfono.
  - Eliminación de la colisión entre el Toast de notificaciones y el botón flotante de WhatsApp mediante `hidden sm:flex`, liberando el tercio inferior del teléfono para navegación táctil sin obstáculos.
  - Simplificación del ticker superior en móvil a una sola línea limpia y centrada, eliminando ruido visual antes del encabezado.
  - Pestañas de Showcase rediseñadas con botones táctiles simétricos (`grid grid-cols-2`) para fácil accionamiento con el pulgar.
  - Escalado de títulos y textos en el simulador a `text-xl sm:text-2xl font-black` y `text-base` para una lectura amplia y contundente sin efecto de reducción.

## [2026-09-27] - Restauración de Fidelidad de Imagen 1 (Google Maps Showcase) y Entorno Real de WhatsApp (Bento 3)
- **Causa Raíz de Imagen 1 Ausente:**
  - Al habilitar la arquitectura de doble pilar, el showcase de Google Maps fue desplazado a la Pestaña 2 y oculto con `class="hidden"` por defecto. El usuario percibió que el diseño previo se había eliminado.
  - Solución: Se restableció la Pestaña de Google Maps (`tabSeoContent`) como la vista activa predeterminada en el primer render, restaurando fielmente la barra macOS con la URL de búsqueda, los pines dinámicos (`#1 Piantini +180 llamadas`, `#1 Naco & Bella Vista +240 llamadas`, `#1 Santiago RD +160 llamadas`), el radio de 15 km, la tasa de CTR de 68.4% y las tarjetas de clasificación con microdatos y badges.
- **Autenticidad de Entorno WhatsApp en Bento Card 3:**
  - Se transformó la tarjeta de click-to-chat en una réplica de WhatsApp oficial:
    - Fondo con patrón de doodles característico de WhatsApp sobre `#efeae2`.
    - Cabecera oficial color `#008069` con avatar de ISAPromoRD, indicador verificado y estado 'en línea'.
    - Píldora de fecha 'HOY' centrada.
    - Burbujas de mensaje con estilos nativos (cliente entrante en blanco `#ffffff`, respuesta de ISAPromoRD en verde suave `#D9FDD3` con doble check azul `#53bdeb`).
    - Barra inferior nativa `#F0F2F5` con iconos de emoji, clip de adjuntos, campo de texto 'Escribe un mensaje...' y botón circular verde `#00A884` con micrófono.
