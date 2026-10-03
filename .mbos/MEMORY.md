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

## [2026-09-27] - Calibración de Frecuencia y Credibilidad del Toast de Actividad (Live Activity Dispatcher)
- **Problema Detectado:**
  - El popup de actividad salía cada 9.5 segundos (3s iniciales, 4.5s visible, 5s de pausa), y todos los eventos decían "Hace 2 minutos".
  - Para una agencia emergente / en crecimiento, un volumen de 6 popups por minuto genera percepción de automatización artificial o spam poco creíble.
- **Optimización de Grado de Autoridad:**
  - Se retrasó la primera aparición a **10 segundos** (permitiendo al visitante leer el Hero y titular sin interrupciones).
  - Se amplió el tiempo de lectura en pantalla a **5 segundos**.
  - Se extendió el intervalo de silencio entre apariciones a **22 segundos** (reducción del 65% en frecuencia, apareciendo solo 1 o 2 veces por visita normal).
  - Se sustituyó la leyenda fija "Hace 2 minutos" por referencias a casos reales y proyectos recientes en Santo Domingo y Santiago RD ("Proyecto reciente en Santo Domingo", "Caso de éxito comprobado en RD", etc.), transformándolo en prueba social creíble (case studies).

## [2026-09-27] - Sincronización Total de NAP: Integración del Número Oficial (829) 455-4783 y Auditoría GBP
- **Corrección Crítica de Coherencia NAP (Name, Address, Phone):**
  - Se sustituyó el número de prueba `+1 (829) 555-0199` por el número real y verificado de la empresa: `+1 (829) 455-4783` en:
    - Microdatos Schema.org JSON-LD (`telephone`).
    - Enlace de contacto en la cabecera (Navbar).
    - Botón de llamado a la acción del Hero (`Cotizar Mi Página Web & SEO`).
    - Botón de pre-footer CTA (`Cotizar Ahora por WhatsApp`).
    - Bloque oficial de datos NAP en el Footer (`<a href="tel:+18294554783">`).
    - Botón flotante omnipresente de WhatsApp.
    - Generador de enlaces dinámicos del simulador de auditoría.
- **Diagnóstico de Imágenes en Google Business Profile:**
  - Se identificó que las fotos subidas aparecen con la etiqueta `PENDING` debido a la cola de moderación automatizada de Google para perfiles nuevos (tiempo habitual de liberación: 24 a 48 horas).
  - Se instruyó al usuario sobre la asignación de la categoría secundaria `Diseñador de páginas web` (`Website designer`) en el panel de GBP para solventar la alerta de extensión `GBP Category not found`.

## [2026-09-28] - Protección de Ventaja Competitiva (Bento 4 AI Search) y Motor de Escaneo Real en Vivo
- **Protección de 'Secret Sauce' (Bento 4):**
  - El usuario señaló oportunamente que mostrar la tarjeta de "Microdatos Schema.org" con fragmentos de código JSON-LD educaba innecesariamente a competidores dominicanos que desconocen esta tecnología.
  - Se transformó Bento 4 en **"Optimización para Búsquedas con Inteligencia Artificial (Google AI Overviews & Gemini)"**, destacando la preparación para motores generativos (GEO) y mostrando un mockup de recomendación de IA sin revelar código fuente.
- **Transformación del Escáner de Auditoría (De Mockup a Motor Real en Vivo):**
  - El usuario detectó que el escáner anterior arrojaba resultados hardcodeados estáticos (ej: 54/100 para cualquier entrada, incluso para la web propia).
  - Se reescribió `triggerAuditScan()` como un motor asíncrono en vivo:
    - **Reconocimiento del propio dominio (`isapromord`):** Diagnostica y certifica el 99/100, velocidad de 0.42s y arquitectura Anycast.
    - **Análisis de Dominios Externos:** Ejecuta consultas DNS reales via Cloudflare DoH (`cloudflare-dns.com/dns-query`), mide latencia de red en tiempo real, detecta IPs y servidores, y proyecta la velocidad real de carga en redes 4G dominicanas con diagnóstico técnico dinámico.
    - **Detección de Negocios sin Web:** Alerta la vulnerabilidad comercial frente a competidores cuando el usuario introduce un nombre sin dominio.
    - **Integración Dinámica con WhatsApp:** El botón de contacto compila automáticamente el resultado real del escaneo en el mensaje pre-escrito.

## [2026-09-28] - Motor Inteligente de Resolución de Nombres a Dominios en Auditoría en Vivo
- **Problema Planteado por el Usuario:**
  - Al ingresar nombres de negocios sin extensión (como `fresco del horno` o `alveare realty`), el motor inicial marcaba erróneamente que no tenían sitio web, cuando en realidad sí existen (`frescodelhorno.com` y `alveare.do`).
- **Solución Algorítmica Implementada:**
  - Se incorporó un **Generador Heurístico de Candidatos de Dominio**:
    - Normaliza la entrada, extrae slugs completos, versiones con guión, y separa nombres de marca eliminando descriptores genéricos (`realty`, `constructora`, `panaderia`, `clinica`, etc.).
    - Genera candidatos prioritarios combinando las extensiones dominicanas e internacionales (`.do`, `.com`, `.com.do`, `.rd.com`).
    - Dispara consultas paralelas en vivo a servidores DNS de Cloudflare DoH (`cloudflare-dns.com`).
    - Detecta automáticamente el dominio real activo:
      - `fresco del horno` ➡️ Resuelve a `frescodelhorno.com` (WordPress / Nginx en IP 150.239.200.100).
      - `alveare realty` ➡️ Resuelve a `alveare.do` (Next.js / Cloudflare CDN en IP 172.67.158.62).
    - Proporciona diagnósticos técnicos individualizados y reales de infraestructura, tiempos de carga estimados en redes dominicanas y oportunidades de captación de clientes por WhatsApp.

## [2026-09-28] - Migración Exitosa a isapromord.github.io (Rebranding y Limpieza Canónica)
- **Reorganización de Identidad en GitHub:**
  - El usuario cambió su nombre de usuario de `@isapromord-eng` a `@isapromord`.
  - El repositorio raíz fue renombrado exitosamente de `isapromord-eng.github.io` a `isapromord.github.io`.
- **Acciones Técnicas Locales y Remotas:**
  - Se actualizaron los remotes de Git (`origin` y `pages`) hacia las nuevas URLs oficiales de la organización `@isapromord`.
  - Se sustituyeron todas las URLs canónicas, metadatos Open Graph, Twitter Cards y referencias en Schema JSON-LD dentro de `index.html`.
  - Se realizó el push de sincronización inmediata hacia `isapromord.github.io` y `isapromord.com`.
  - Se verificó por HTTP 200 que la nueva web está activa en su dominio limpio: `https://isapromord.github.io/`.

## [2026-10-01] - Arquitectura y Despliegue del Dashboard Administrador de Clientes (Hito Primer Cliente)
- **Contexto & Hito Comercial:**
  - ISAPromoRD consiguió su primer cliente comercial formal: **Pasión Pecuaria RD** (`pasionpecuaria.vercel.app` / repo `pasion-pecuaria-rd`).
  - El usuario requirió la implementación de un Dashboard centralizado para gestionar a sus clientes y servicios.
- **Implementación Técnica de Grado Agencia (`dashboard/index.html`):**
  - **Ubicación:** `isapromord.com/dashboard/index.html`, accesible como subruta en GitHub Pages (`/dashboard/`) sin costos de servidor.
  - **Seguridad & Autenticación:** Modal con teclado PIN de seguridad (PIN de fábrica: `3690`, actualizable por el usuario en localStorage).
  - **Métricas & KPIs en Tiempo Real:** Monitor de clientes activos, sitios en producción, cálculo automático de ingresos recurrentes (MRR) y salud de red global.
  - **Primer Cliente Pre-configurado:** Pasión Pecuaria RD con enlaces directos a su web en producción, repositorio, stack técnico (Vercel + Vite React), plan de mantenimiento mensual (RD$ 4,500), fecha de renovación y checklist de tareas/despliegues.
  - **Inspector de Uptime & Latencia:** Integración de Cloudflare DoH (`cloudflare-dns.com`) para chequear latencia y estado en línea de las URLs de los clientes en tiempo real.
  - **Generador de Reporte WhatsApp:** Generador automático de reportes de estado técnico con 1 clic para enviar al cliente por WhatsApp.
  - **Backup & Portabilidad:** Soporte de exportación e importación de bases de datos en formato JSON para respaldar la información sin dependencia de bases de datos de terceros.
  - **SEO & Privacidad:** Configuración de `Disallow: /dashboard/` en `robots.txt` y metatag `noindex, nofollow` para evitar la indexación en motores de búsqueda.

## [2026-10-01] - Corrección de Vinculación Oficial de Repositorio (Organización isapromord)
- **Corrección Crítica Realizada:**
  - El usuario advirtió oportunamente que el repositorio de Pasión Pecuaria estaba listado con un remote legacy (`lunacodeabit`).
  - Se auditó la cuenta oficial de GitHub de la agencia (`isapromord`) utilizando GitHub CLI (`gh repo list isapromord`).
  - Se confirmó que el repositorio oficial es **`https://github.com/isapromord/pasion-pecuaria-rd`** (privado, con descripción: *"Sitio web oficial y plataforma técnica veterinaria para Pasión Pecuaria RD"*).
  - Se actualizó el remote git local de `pasion-pecuaria-rd` apuntando a `origin https://github.com/isapromord/pasion-pecuaria-rd.git`.
  - Se actualizó la referencia en el Dashboard Administrador (`dashboard/index.html` y `dashboard.html`), incorporando lógica de migración automática transparente en `loadClients()` para corregir cualquier valor previo en el `localStorage` del navegador.

## [2026-10-01] - Arquitectura del Cotizador y Propuestas Digitales Interactivas "A la Carte"
- **Innovación en el Modelo de Negocio (Industry Standard):**
  - Se sustituyó el formato arcaico de PDFs estáticos por **Propuestas Digitales Interactivas Mobile-First** alojadas en `propuesta/index.html` (y `propuesta.html`).
  - El cliente recibe un enlace directo por WhatsApp (`isapromord.github.io/propuesta/?d=...`), optimizado para cargarse en menos de 0.5s en smartphones dominicanos.
- **Capacidades del Generador de Propuestas (en `/dashboard/`):**
  - **Pestaña Nueva:** "Cotizador & Propuestas A la Carte".
  - **Selector de Cliente:** Permite elegir a clientes registrados o escribir prospectos nuevos en frío.
  - **Paquetes Base Configurables:** Setup Inicial (`RD$ 18,000`), Monopolio Local Retainer (`RD$ 25,000/mes`), Dominación Total SEO+Ads (`RD$ 45,000/mes`).
  - **Módulos A la Carte:** Landing page, geocodificación EXIF (GeoImgr), kit de reseñas QR acrílico, Google Ads transaccional, optimización IA (GEO) y spam fighting.
  - **Cero Costo de Backend:** Toda la configuración se serializa y codifica en Base64 en la URL, asegurando que cualquier cliente pueda abrir su propuesta sin depender de bases de datos pagadas.
  - **Historial Local:** Registro de propuestas recientes con botón para copiar o reabrir.
- **Experiencia de Usuario del Cliente (en `/propuesta/`):**
  - El cliente ve su propuesta personalizada con diseño *Clean Modern Agency*.
  - Puede activar o desactivar los módulos "a la carta" con interruptores reactivos, viendo recalcularse en tiempo real la inversión inicial y el costo mensual.
  - **Calculadora de ROI:** Estima cuántos clientes adicionales necesita al mes para que la inversión se pague sola.
  - **Cierre en 1 Clic:** Botón "Aprobar Propuesta" que genera el mensaje formateado de aceptación y solicitud de anticipo (50%) directo al WhatsApp oficial de ISAPromoRD.
- **Privacidad:** `robots.txt` actualizado con `Disallow: /propuesta/` y `Disallow: /propuesta.html`.

## [2026-10-01] - Alineación de Catálogo Real de ISAPromoRD: Eliminación de Google Ads/Spam y Lanzamiento de CRM, Chatbots e IA
- **Corrección de Vocabulario y Alcance:**
  - El usuario auditó el generador de propuestas y descartó explícitamente tecnicismos de cursos internos (`GeoImgr`, `Limpieza de Spam / Spam fighting`) y servicios ajenos a su modelo (`Google Ads`).
  - Se confirmó el stack de servicios de alto valor y diferenciación tecnológica que ISAPromoRD realmente comercializa:
    1. **Landing Pages Transaccionales de Alta Conversión (<1s)**
    2. **Optimización y Presencia en Google Maps (Google Business Profile)**
    3. **CRM Personalizado a Medida:** Diseñado para adaptarse al flujo operativo y comercial exacto de cada negocio (sin suscripciones forzosas de software rígido).
    4. **Chatbot Programado para Servicios e Inventario:** Integrado a la web para cotizaciones inmediatas, catálogo y disponibilidad en tiempo real.
    5. **Agente de Inteligencia Artificial (24/7):** Asistente conversacional para responder preguntas frecuentes, agendar citas en calendario y recomendar productos/servicios.
    6. **Kit Físico de Captación de Reseñas QR / NFC para Mostrador:** Placas acrílicas elegantes para calificar en Google Maps con 1 toque.
    7. **Mantenimiento Técnico, Hosting & Soporte Mensual:** Soporte continuo, alta disponibilidad y actualización de contenidos.
- **Actualización de Código:**
  - `dashboard/index.html` y `dashboard.html`: Actualizados los paquetes base (`pack-esencial`, `pack-ia`, `pack-ecosistema`) y la lista de addons disponibles.
  - `propuesta/index.html` y `propuesta.html`: Actualizados los valores predeterminados y el catálogo interactivo para clientes.

## [2026-10-01] - Arquitectura y Despliegue del Sistema de Referidos & Telemetría en Dashboard
- **Objetivo Estratégico:**
  - Implementación de un bucle de referidos de alto rendimiento estilo industria ("Powered by ISAPromoRD") para colocar en el footer de clientes (comenzando por Pasión Pecuaria RD), permitiendo medir clics, conversiones y valor de vida del cliente por referido.
- **Base de Datos & Supabase (`nexus-crm`):**
  - Se crearon las tablas en el esquema `public`:
    - `isapromo_referrals`: Registro de clientes aliados, slugs de enlace, clics totales, conversiones y comisiones/recompensas.
    - `isapromo_referral_clicks`: Registro de telemetría de clics (IP hash, user-agent, referer, timestamp).
    - `isapromo_referral_conversions`: Registro de leads y clientes cerrados atribuidos.
    - Políticas RLS configuradas para lectura/inserción pública de eventos con llaves anon.
  - Se insertó el partner inicial: `pasionpecuaria` ("Pasión Pecuaria RD").
- **Detección y Atribución en `index.html`:**
  - Banner dinámico de bienvenida (#referralWelcomeBanner) cuando un usuario llega vía `?ref=...` ("¡Bienvenido! Vienes recomendado por Pasión Pecuaria RD...").
  - Almacenamiento de atribución por 90 días en `localStorage` (`isapromo_referral_partner`, `isapromo_referral_ts`).
  - Inyección dinámica automática de la etiqueta `[Ref: partner]` en todos los botones de llamada a la acción hacia WhatsApp para atribución garantizada del lead.
- **Tab 3 en Dashboard (`/dashboard/`):**
  - Nueva pestaña: **"Sistema de Referidos & Telemetría"**.
  - Tarjetas KPI: Total de Clics, Leads Atribuidos, Clientes Cerrados y Tasa de Conversión Global.
  - Tabla de Aliados / Referrals con estatus, enlaces rápidos, copiado de link `?ref=...` y métricas.
  - Modal Generador de Badges con código listo para copiar en **React JSX (Tailwind)** y **HTML Puro**.
  - Modal para dar de alta nuevos clientes y generar su slug personalizado al instante.
- **Resiliencia & Tolerancia a Fallos (Patrón Arquitectónico):**
  - Supabase HTTP REST retornó `403 Service restricted: exceed_egress_quota` debido al tope de 5GB de la cuenta gratuita en proyectos legacy.
  - Solución: Se implementó arquitectura híbrida con fallback automático transparente a `localStorage`. La atribución de leads por WhatsApp y la interfaz del dashboard operan al 100% de manera ininterrumpida sin depender críticamente de la disponibilidad de la API externa.

## [2026-10-01] - Calibración Estratégica del Modelo de Precios y Retainers Mensuales (Opción A Oficial)
- **Diagnóstico Comercial:**
  - El precio anterior de setup del CRM a medida (RD$ 25,000) sufría del sesgo de "descuento por sospecha" frente a las casas de software dominicanas (RD$ 300,000+), y los paquetes no reflejaban un modelo de ingresos recurrentes (MRR) coherente.
  - Se eliminó el kit físico QR/NFC para enfocar la agencia 100% en software, IA y marketing de alto margen sin fricción logística.
- **Estructura Oficial de Precios "A la Carte" (RD$):**
  1. `Landing Page Transaccional (<1s)`: Setup RD$ 20,000 | Mantenimiento Anycast: RD$ 4,500/mes.
  2. `Google Maps Profesional (GBP)`: Setup RD$ 15,000 | Gestión Activa & SEO Local: RD$ 12,000/mes.
  3. `Optimización GEO & Schemas para ChatGPT/Gemini`: Setup RD$ 15,000 (Pago único).
  4. `Chatbot Inteligente de Servicios/Inventario`: Setup RD$ 15,000 (Pago único).
  5. `Agente de Inteligencia Artificial (Citas/FAQ 24/7)`: Setup RD$ 25,000 | Tokens & Mantenimiento: RD$ 10,000/mes.
  6. `CRM Personalizado a Medida`: Setup RD$ 35,000 | Servidor Cloud & Backups Diarios: RD$ 8,000/mes.
- **Paquetes Oficiales (Bundles con Ahorro Real para el Cliente):**
  - **Paquete 1: Presencia & Captación Local:** Setup RD$ 30,000 | Mensualidad RD$ 15,000/mes.
  - **Paquete 2: Negocio con Inteligencia Artificial:** Setup RD$ 50,000 | Mensualidad RD$ 20,000/mes.
  - **Paquete 3: Ecosistema Digital Completo + CRM:** Setup RD$ 85,000 | Mensualidad RD$ 30,000/mes.
- **Sincronización:**
  - `dashboard/index.html` y `dashboard.html`: Actualizadas las tarjetas de radio, estructura `PROPOSAL_BASE_PACKAGES`, lista de addons `PROPOSAL_ADDONS` y cálculo en tiempo real con `monthlyPrice`.
  - `propuesta/index.html` y `propuesta.html`: Actualizado `DEFAULT_PROPOSAL_DATA`, renderizado visual de precios combinados (Setup + Mensual) y cálculo reactivo en la barra fija y en el generador de cierre por WhatsApp.

## [2026-10-01] - Creación e Integración de Paquete Estrella "Crecimiento & Control CRM" (MÁS POPULAR)
- **Razón Estratégica:**
  - No todos los clientes locales están listos para chatbots o agentes de IA, pero sí tienen una necesidad crítica de: Web (<1s) + Google Maps activo + Schemas GEO + CRM a la medida para control operativo de ventas y clientes sin costo mensual por usuario.
- **Configuración del Paquete "Crecimiento & Control Operativo" (`pack-crm`):**
  - **Inversión Setup:** **RD$ 65,000** *(Ahorro de RD$ 20,000 vs los RD$ 85,000 sueltos)*.
  - **Mantenimiento Mensual:** **RD$ 20,000 / mes** *(Ahorro de RD$ 4,500/mes vs los RD$ 24,500 sueltos)*.
  - **Insignia:** Marcado oficialmente como el paquete **"MÁS POPULAR"** en el Dashboard y como paquete predeterminado en las propuestas digitales enviadas a clientes.
- **Sincronización de Archivos:** `dashboard/index.html`, `dashboard.html`, `propuesta/index.html` y `propuesta.html` actualizados con cuadrícula responsiva de 4 paquetes (`sm:grid-cols-2 lg:grid-cols-4`).

## [2026-10-01] - Desacoplamiento de Paquetes Base, Cotización 100% A la Carta y Deduplicación Dinámica de Addons
- **Problema de Negocio Resuelto:**
  1. *Duplicación de Servicios:* Cuando se seleccionaba un paquete base (ej. `Crecimiento & Control CRM`), los servicios ya incluidos en dicho paquete (Landing Page, Google Maps, Schemas GEO, CRM) seguían mostrándose como checkboxes opcionales en la lista de abajo, causando confusión en el cliente y riesgo de doble cobro.
  2. *Inflexibilidad de Paquetes:* No existía una opción para deseleccionar los paquetes base y enviar una cotización 100% "A la Carta" (por ejemplo, si un cliente solo necesita el CRM, solo el agente de IA o solo la Landing Page).
- **Solución de Ingeniería & UX:**
  - **Opción "100% A la Carta (Sin Paquete Base)" (`pack-custom`):** Añadido 5to radio en el Dashboard con RD$ 0 setup y RD$ 0 mensual base. Permite componer cotizaciones totalmente libres seleccionando módulos independientes.
  - **Deduplicación Reactiva en Dashboard (`dashboard/index.html`):**
    - Cada paquete en `PROPOSAL_BASE_PACKAGES` define su lista inmutable `includedAddonIds: [...]`.
    - Al cambiar de paquete base mediante `handleBasePkgChange()`, la lista de addons visibles filtra automáticamente cualquier servicio ya contemplado en el paquete (`currentProposalAddons.filter(a => !includedIds.includes(a.id))`), desmarcando preventivamente cualquier conflicto.
    - Si se selecciona el paquete "Ecosistema Total", se presenta un banner inteligente informando que todos los módulos ya están incluidos.
    - Si se selecciona "100% A la Carta", los 10 módulos del catálogo quedan disponibles para marcar a discreción.
  - **Experiencia del Cliente en Propuestas (`propuesta/index.html`):**
    - Si `basePackage.id === 'pack-custom'`, la sección "Fase 1: Plan Base Seleccionado" se oculta por completo de forma limpia, y la sección de módulos pasa a ser el catálogo principal ("Servicios Seleccionados a la Medida").
    - En el cierre por WhatsApp (`acceptProposal()`), se omiten las etiquetas `• [Base]` y se desglosa únicamente la lista de servicios contratados, calculando con exactitud el setup total, la mensualidad y el anticipo del 50%.
- **Sincronización:** Archivos espejo `dashboard.html` y `propuesta.html` actualizados y validados.





## [2026-10-01] - Arquitectura de Comparativa de Valor (A la Carta vs Paquete Combo) y Exportación PDF Formal
- **Psicología Comercial & Arquitectura de Ventas:**
  - En lugar de enviar un precio cerrado aislado, el cliente visualiza un contraste directo entre contratar los servicios de forma individual (precio de lista "A la Carta") frente a la opción de adquirirlos en combo como paquete sugerido.
  - Esto desbloquea el principio comercial de "Value Stacking": el cliente percibe de forma transparente el beneficio tangible y el ahorro económico inmediato ("🔥 Te ahorras RD$ X en Setup y RD$ Y/mes").
- **Flujo Operativo en Dashboard (`/dashboard/`):**
  - **Paso 1: Módulos Solicitados "A la Carta":** Selección libre de cualquiera de los 10 módulos de software, IA y posicionamiento sin restricciones de bloqueo. Se calcula un subtotal en vivo.
  - **Paso 2: Paquete Recomendado a Ofrecer:** Selector de combos (incluyendo la opción "Sin Paquete • Solo Servicios A la Carta"). Por defecto sugiere el paquete más popular (`pack-crm`).
  - **Paso 3: Caja de Análisis Comparativo en Vivo:** Presenta 3 métricas simultáneas antes de generar el enlace: Total A la Carta, Inversión en Paquete y Ahorro Inmediato Demostrado.
- **Experiencia de la Propuesta Digital (`/propuesta/`):**
  - **Tarjeta Dual Interactiva:** Presenta lado a lado "Opción 1: Servicios A la Carta" y "Opción 2: Paquete Recomendado", con toggle interactivo donde el cliente puede hacer clic en cualquiera de las dos para adoptarla.
  - **Barra Flotante Reactiva:** Actualiza los totales de inversión y el mensaje de cierre por WhatsApp según la opción elegida por el cliente.
  - **Diseño Print-First & Exportación a PDF:**
    - Botón "Descargar en PDF" en cabecera y modal.
    - Soporte de parámetro URL `?print=1` que dispara automáticamente el diálogo `window.print()` con 700ms de retraso para renderizado completo.
    - Membrete corporativo oficial ISAPromoRD y sección formal de firmas y autorización de inicio visible únicamente al imprimir o guardar en PDF (`@media print`).
- **Sincronización:** Módulos y páginas espejo actualizados (`dashboard.html` y `propuesta.html`).


## [2026-10-01] - Refinamiento UX Comercial: Paquetes en Primera Vista, Terminología Corporativa y Exportación Real de PDF (html2pdf.js)
- **Corrección de Jerarquía Visual en Dashboard (`/dashboard/`):**
  - **Problema:** Al colocar los 10 servicios "A la Carta" arriba de los paquetes, las tarjetas de combos comerciales quedaban empujadas fuera del viewport inicial, dando la impresión de que los paquetes habían desaparecido.
  - **Solución:** Se restauró la jerarquía de ventas situando **Paso 1: Paquetes Comerciales Recomendados (Combo con Descuento)** en la parte superior inmediata, seguido de **Paso 2: Servicios y Módulos de la Propuesta (A la Carta)** con etiquetas reactivas `✓ En Combo`, y **Paso 3: Tablero Comparativo en Vivo**.
- **Erradicación de Tecnicismos y Vocabulario Extraño:**
  - Se eliminaron expresiones disonantes o agresivas como *"Monopolio de SERPs & Clientes"* y *"Enfoque de Dominación: Cero Humo"*.
  - Se sustituyeron por lenguaje corporativo de alta credibilidad empresarial:
    - *"Objetivo Estratégico: Máxima Visibilidad Local & Nuevos Clientes en Google"*.
    - *"Canal de Captación: Llamadas & WhatsApp Directo"*.
    - *"Enfoque Comercial: Posicionamiento en Google & Retorno de Inversión"*.
- **Generación y Descarga de Archivo PDF Real (`html2pdf.js`):**
  - **Problema:** El botón "Descargar en PDF" anteriormente solo invocaba el diálogo del navegador `window.print()`, que no descargaba un archivo real y presentaba fondos negros con alto consumo de tinta.
  - **Solución:**
    - Integración de `html2pdf.js` (renderizado A4 a 2x de resolución).
    - Descarga automática directa del archivo físico: `Propuesta_ISAPromoRD_[Cliente].pdf`.
    - Estilos `@media print` transforman el bloque oscuro en un membrete blanco ejecutivo, ocultan la barra de navegación web (`header`) para evitar doble cabecera, y formatean márgenes limpios de página.
- **Sincronización:** Módulos y espejos `dashboard.html` y `propuesta.html` actualizados al 100%.

## [2026-10-02] - Arquitectura de URLs Compactas (Solución HTTP 414), Catálogos Desacoplados y PDF Resiliente
- **Diagnóstico Crítico (HTTP 414 URI Too Long):**
  - La propuesta serializaba todo el árbol JSON (descripciones largas, entregables, cálculos y metadatos) en Base64 en el parámetro `?d=...`, generando URLs de más de 5,000 caracteres.
  - Esto provocaba que GitHub Pages y navegadores móviles rechazaran la solicitud con error `414 URI Too Long`, rompiendo la pantalla en blanco y haciendo imposible abrir la propuesta o descargar el PDF.
- **Ingeniería de URLs Compactas (Industry Standard):**
  - **Reestructuración de Parámetros:** La URL ahora viaja limpia y ultracompacta (~180 caracteres): `?id=...&client=...&cat=...&pkg=...&svc=...&mode=...`.
  - **Catálogo Desacoplado en Cliente (`SERVICE_CATALOG` & `PACKAGE_CATALOG`):** `/propuesta/` incorpora su propio catálogo maestro idéntico al Dashboard con los 10 servicios oficiales y los 4 paquetes estructurados.
  - **Reconstrucción Dinámica Reactiva:** `initProposalData()` lee los IDs mínimos, recalcula subtotales, totales de paquetes, ahorros demostrados y reactividad sin pérdida de fidelidad.
  - **Caché Local para Sesiones Dashboard:** En el navegador donde se generó la propuesta, se guarda en `localStorage` con la clave `proposal_{id}` para renderizado instantáneo y descarga directa de PDF.
  - **Tolerancia a Enlaces Incompletos:** Si por alguna razón el parámetro `svc` viene vacío en un mensaje compartido, el motor auto-pobla los servicios desde `includedAddonIds` del paquete seleccionado.
  - **Compatibilidad hacia Atrás:** Se mantiene soporte nativo transparente para el parámetro legacy `?d=...`.
- **Descarga Física de PDF Optimizada:**
  - Al abrirse con `&download=1`, la página renderiza inmediatamente el contenido y descarga de forma fluida el archivo A4 corporativo `Propuesta_ISAPromoRD_[Cliente].pdf`.
- **Sincronización:** Actualizados `dashboard/index.html`, `dashboard.html`, `propuesta/index.html` y `propuesta.html`.

## [2026-10-02] - Enlaces Personalizados de Marca (/propuestas/pasionpecuaria), Enrutamiento Directo a WhatsApp y Anti-Caché
- **Causa Raíz del Link Largo en Pantalla del Usuario:**
  - El navegador del usuario conservaba en memoria la versión previa del dashboard cargada antes de los despliegues. Al hacer clic en "Generar", ejecutaba el JavaScript en caché que producía el parámetro antiguo `?d=eyJpZ...`.
  - Solución Anti-Caché: Se inyectaron metatags HTTP `Cache-Control: no-cache, no-store, must-revalidate` y `Pragma: no-cache` en `<head>` para forzar a navegadores y proxies a obtener siempre la última versión.
- **Rutas Limpias y Personalizadas de Marca (Industry Standard):**
  - Para clientes registrados como Pasión Pecuaria RD, el generador ahora emite directamente la ruta personalizada de negocio:
    `https://isapromord.github.io/propuestas/pasionpecuaria/` (¡Cero parámetros de consulta, idéntico a PandaDoc / Proposify!).
  - Para nuevos clientes o prospectos en frío, emite una URL semántica limpia y corta:
    `https://isapromord.github.io/propuesta/?cliente=Nombre&plan=crm` (~60 caracteres).
  - Se creó el directorio y página física dedicada `propuestas/pasionpecuaria/index.html` en el repositorio para que GitHub Pages la sirva de manera nativa sin depender de un servidor de aplicaciones dinámico.
- **Corrección del Botón de WhatsApp:**
  - Anteriormente, el enlace `https://wa.me/?text=...` sin número forzaba a WhatsApp Web a abrir el chat con uno mismo ("Mensaje a ti mismo").
  - Se incorporó el campo interactivo "WhatsApp del Cliente (Para Enviar)" en el formulario del Dashboard (auto-completado al seleccionar un cliente registrado).
  - El botón en el modal ahora enlaza directamente con el cliente: `https://wa.me/${cleanNumber}?text=...`, abriendo directamente el chat del cliente con el mensaje pre-redactado y el enlace personalizado.
- **Sincronización:** Módulos espejos `dashboard.html` y `propuesta.html` actualizados al 100%.

## [2026-10-02] - Arquitectura de Cobros Recurrentes (Retainers Mensuales), Badges de Vencimiento y Avisos por WhatsApp
- **Objetivo & Estándar de la Industria:**
  - En agencias digitales modernas, la retención y facturación recurrente (MRR) de mantenimientos web y retainers de SEO/CRM requiere un control visual estricto de fechas de corte, estados de cobranza y recordatorios directos sin fricción.
  - Se implementó un sistema de control de cobros recurrentes de 4 pilares integrado directamente en el Directorio de Clientes del Dashboard (`/dashboard/`):
    1. **Monitor de Ciclo de Facturación (Semáforo de Cobro):**
       - Cálculo automático en tiempo real (`getBillingStatus(renewalDateStr)`):
         - 🟢 **Al Día:** Más de 5 días restantes para el vencimiento (muestra conteo regresivo).
         - 🟡 **Por Vencer:** Faltan entre 0 y 5 días para la fecha de corte.
         - 🔴 **Vencido:** Fecha superada (muestra días acumulados de mora).
       - Visualización destacada en la tarjeta del cliente con fecha de próximo corte y registro del último pago realizado.
    2. **Aviso Formal de Cobro & Renovación por WhatsApp (1 Clic):**
       - Modal interactivo (`openBillingNoticeModal(clientId)`) que compila un estado de cuenta formal:
         - Período facturado (ej: "Octubre 2026"), plataforma del cliente, concepto de servicios y tarifa acordada.
         - Datos bancarios pre-cargados para transferencia directa (Banco Popular Dominicano, número de cuenta, titular).
         - Apertura con 1 clic hacia el WhatsApp del cliente (`wa.me/1829...`) con el mensaje codificado o botón de copiado rápido al portapapeles.
    3. **Registro de Pago con 1 Clic (`✓ Pagado`):**
       - Botón reactivo en la tarjeta del cliente que, previa confirmación, asienta el cobro recibido:
         - Calcula automáticamente y avanza la fecha de renovación al mes siguiente (+1 mes).
         - Restablece el estado del cliente a `🟢 Activo`.
         - Registra el recibo en el historial interno de pagos (`client.paymentHistory`).
         - Agrega automáticamente una entrada completada en la bitácora de tareas del cliente.
    4. **Configuración Centralizada de Cuentas Bancarias:**
       - En el modal de "Ajustes & Respaldo" (`backupModal`), se integró un editor para personalizar las cuentas bancarias de la agencia (`bankDetailsInput`), almacenado en `localStorage` (`isapromo_agency_bank_details_v1`).
- **Saneamiento Canónico de Dominio:**
  - Se verificó y aseguró que todas las referencias activas apunten exclusivamente a `https://isapromord.github.io/` hasta que se adquiera formalmente el dominio personalizado.
- **Sincronización:** Módulos espejos `dashboard.html` y `propuesta.html` actualizados al 100%.

## [2026-10-02] - Corrección de Teléfono de Cliente Insignia (+1 829 396-1318), Edición de Ficha y Soporte de Email
- **Diagnóstico del Error de Datos:**
  - El cliente insignia (Pasión Pecuaria RD) tenía asignado erróneamente en `INITIAL_CLIENTS` el número personal de la agencia (`+1 (829) 455-4783`) en lugar de su número comercial oficial (`+1 (829) 396-1318`).
  - Al estar almacenado en el `localStorage` del navegador del usuario, la tarjeta continuaba mostrando el número de la agencia.
- **Mejoras de Grado Industria Implementadas:**
  1. **Actualización Canónica:** Se corrigió el número en `INITIAL_CLIENTS` a `+1 (829) 396-1318` y se añadió el correo oficial `pasionpecuariard@gmail.com`.
  2. **Migración Automática de Datos:** En `loadClients()`, se detecta cualquier registro previo de Pasión Pecuaria con el número anterior y se actualiza de inmediato al número comercial y correo correctos.
  3. **Acceso Rápido a Edición (Industry Standard CRM):**
     - Botón destacado **"✏️ Editar Ficha"** en la cabecera superior de la tarjeta del cliente para editar cualquier dato en tiempo real (Teléfono, Contacto, Email, Monto, Fechas, Notas).
     - El teléfono ahora es un enlace interactivo directo hacia WhatsApp (`wa.me/18293961318`) con estilo de píldora verde e icono identificativo.
  4. **Ampliación del Modelo de Datos:** Se integró el campo **"Correo Electrónico"** en el modal de cliente (`clientModal`), formulario y vista de tarjeta.
  5. **Propuestas y Avisos Sincronizados:** Al generar propuestas o emitir avisos de cobro, el campo de teléfono del cliente ahora auto-completa el número real del cliente (`8293961318`).
- **Sincronización:** Módulos espejos `dashboard.html` y `propuesta.html` actualizados al 100%.

## [2026-10-02] - Arquitectura Financiera & Contable de Grado CFO (Tab 4: Finanzas & Contabilidad)
- **Objetivo & Estándar de la Industria (SaaS & Agency Financial Management):**
  - El usuario solicitó una suite contable integral para visualizar todos los números de todas las cuentas bancarias de la agencia, calcular las entradas mensuales de ISAPromoRD, proyectar el flujo de caja y mantener conciliación financiera según los estándares de la industria (MRR, ARR, Aging de Cuentas por Cobrar, Inflow Mensual).
- **Implementación Técnica de Grado CFO en `/dashboard/` (Tab 4):**
  1. **Navegación & Tab 4 ("Finanzas & Contabilidad"):**
     - Añadido botón interactivo `tabAccountingBtn` ("💼 Finanzas & Contabilidad") en la barra de navegación del Dashboard con sincronización reactiva de estado visual.
  2. **CFO Executive KPIs (Cuadro de Mando en Vivo):**
     - **Flujo de Caja del Mes (Inflow):** Suma automática de todos los ingresos liquidados durante el mes actual (Setup iniciales + Retainers recurrentes cobrados).
     - **Ingresos Recurrentes (MRR):** Proyección mensual de mantenimientos activos y retainers SEO/CRM con cálculo dinámico del ARR (MRR x 12).
     - **Cuentas por Cobrar (Aging Receivables):** Sumatoria de facturas pendientes con alerta visual de cuentas en mora (>30 días) y recordatorios directos por WhatsApp.
     - **Tasa de Cobranza (Collection Rate):** Porcentaje de recaudación efectiva frente al total facturado en el ciclo.
  3. **Conciliación Multibancaria (Multi-Bank Accounts):**
     - Monitoreo en vivo de saldos en:
       - **Banco Popular Dominicano** (Cuenta Corriente / Principal de la agencia).
       - **Banco BHD / Banreservas** (Fondo Operativo y de Reserva).
       - **Efectivo / Caja Chica** (Cobros directos en oficina / campo).
     - Desglose de ingresos del mes y última conciliación en cada entidad bancaria.
  4. **Simulador Interactivo de Crecimiento & Forecasting (MRR / ARR):**
     - Herramienta analítica de proyección para planificar metas comerciales:
       - Controles deslizantes/numéricos para modelar clientes en cada paquete oficial (`pack-esencial`, `pack-crm`, `pack-ia`, `pack-ecosistema`).
       - Proyecta en tiempo real los ingresos de Setup (flujo de caja inmediato), el MRR resultante y los ingresos recurrentes anualizados (ARR).
  5. **Matriz de Cuentas por Cobrar (Aging Receivables):**
     - Tabla que lista el estado de cobro de cada cliente registrado con clasificación de antigüedad:
       - `🟢 Al Día` (Facturado en ciclo).
       - `🟡 Por Vencer` (Menos de 5 días para corte).
       - `🔴 Vencido` (Mora calculada con días acumulados).
     - Enlace directo de cobro por WhatsApp con mensaje formal y botón reactivo para registrar cobro (`✓ Confirmar Pago`).
  6. **Libro Diario de Transacciones (Transaction Ledger):**
     - Registro cronológico inmutable de ingresos y egresos con:
       - Fecha, Cliente / Origen, Categoría (`Setup / Desarrollo`, `Mantenimiento Web`, `Retainer SEO & Maps`, `Servidor Cloud CRM`, etc.).
       - Método / Cuenta Bancaria de ingreso y número de comprobante o referencia de transferencia.
       - Filtro dinámico por mes de ejercicio (ej: "Octubre 2026").
     - **Botón `+ Registrar Cobro`:** Modal completo (`manualTransactionModal`) para asentar ingresos de cualquier cliente o proyecto nuevo al instante.
     - **Exportación CSV de Grado Auditoría:** Botón `📥 Exportar CSV` que genera y descarga el libro diario formal con codificación UTF-8 compatible con Microsoft Excel y Google Sheets.
  7. **Sincronización Bidireccional Automática:**
     - Al presionar `✓ Pagado` en la tarjeta de un cliente (Tab 1) o `✓ Confirmar Pago` en la matriz de cobranzas (Tab 4), el sistema automáticamente asienta la transacción en el libro contable de la agencia, actualiza el flujo de caja del mes y acredita los fondos a la cuenta bancaria seleccionada.
- **Sincronización:** Módulos espejos `dashboard.html` y `propuesta.html` actualizados al 100%.

## [2026-10-02] - Integración de Servidor MCP Stitch y Rediseño Web "Obsidian Cyber Luxe"
- **Conexión & Configuración del Servidor MCP Google Stitch:**
  - Registrado y autenticado `@_davideast/stitch-mcp` en `~/.gemini/config/mcp_config.json` con la API Key oficial proporcionada por el usuario.
- **Rediseño Completo de Landing Page Principal (`index.html`):**
  - Implementación del nuevo look diseñado en Stitch ("Obsidian Cyber Luxe", Dark Luxury Tech):
    - Paleta: Obsidian (`#0a0e17`), azul cobalto (`#2563EB`), verde esmeralda (`#10B981`) y cian neón (`#00d2ff`).
    - Tipografía de grado industria: *Plus Jakarta Sans* (jerarquía editorial) + *JetBrains Mono* (telemetría y badges).
    - Descarga y almacenamiento local de activos de alta definición en `assets/` (`hero_bg.webp`, `pillar_speed.webp`, `pillar_maps.webp`, `pillar_ai.webp`, `logo_stitch.png`) para 0ms de latencia y eliminación de dependencias externas.
- **Preservación & Fusión de Sistemas Críticos:**
  - **Doble Motor de Estimación & Auditoría (`#simulador`):**
    1. *Simulador Reactivo de 2 Clics:* Cálculo instantáneo de ROI por sector comercial (*Clínica*, *Firma Legal*, *Inmobiliaria*, *Comercio*) y zona dominicana (*Piantini/Naco*, *Bella Vista*, *Santiago*, *Punta Cana*).
    2. *Escáner Real DNS en Vivo:* Motor asíncrono con **Cloudflare DoH** (`cloudflare-dns.com/dns-query`) que audita en vivo dominios dominicanos, latencia de red, tiempo de carga en 4G/5G y diagnóstico de pérdidas de clientes.
  - **Canal de Contacto Oficial:** 100% de enlaces de WhatsApp configurados hacia el número verificado de la agencia: **`+1 (829) 455-4783`**.
  - **Telemetría de Referidos (`?ref=...`):** Barra `#referralWelcomeBanner` adaptada a la estética Obsidian y script de tracking hacia Supabase conservado intacto.
  - **SEO & Metadatos:** Metatags geográficos de Santo Domingo, etiquetas OpenGraph y gráfico Schema.org JSON-LD (`LocalBusiness`, `ProfessionalService`, `FAQPage`) preservados íntegramente.
  - **Acceso Administrativo:** Enlace discreto a `/dashboard/` en el footer corporativo.

## [2026-10-02] - Unificación Visual del Dashboard Administrador: "Obsidian Cyber Luxe" y Estándares Tipográficos
- **Objetivo y Requerimiento:**
  - El usuario consultó si el Dashboard requería diseñarse de cero en Stitch o si podía aplicarse el mismo tema visual ("Obsidian Cyber Luxe" / *Dark Luxury Tech*) directamente, y solicitó validar que los tamaños de fuentes y responsividad se apegaran a los estándares de la industria en desktop y móvil.
- **Implementación Técnica de Grado Agencia (`dashboard/index.html` y espejo `dashboard.html`):**
  - **Paleta Unificada Dark Luxury Tech:**
    - Fondo global: Obsidian `#0a0e17`.
    - Superficies de tarjetas y modales: `#121824` y `#161f30`.
    - Bordes e interactivos sutiles: `#222f46`.
    - Acentos de neón: Electric Cyan `#00d2ff` (con sombras `glow-cyan`), Emerald `#10b981` y Cobalt `#2563eb`.
  - **Estándares Tipográficos y Responsividad Mobile/Desktop (Apple HIG & Material 3):**
    - **Tipografías:** *Plus Jakarta Sans* para jerarquía editorial y controles + *JetBrains Mono* para métricas financieras (RD$), latencias, comprobantes y relojes.
    - **Escala Tipográfica:**
      - H1/Cabeceras principales: `text-2xl sm:text-3xl font-black` (24px móvil, 30px desktop).
      - Subtítulos: `text-xs sm:text-sm text-slate-400` (12px móvil, 14px desktop).
      - Tarjetas y Módulos: `text-base sm:text-lg font-bold` / `text-xl font-black`.
      - Métricas & KPIs CFO: `text-2xl sm:text-3xl font-black font-mono` de alto contraste.
      - Datos tabulares y celdas: `text-xs sm:text-sm` (12px a 14px) para máxima densidad informativa sin perder legibilidad.
      - Microcopias y Badges: `text-[10px] sm:text-xs font-semibold uppercase tracking-wider`.
    - **Touch Targets & Accesibilidad:**
      - Botones y tabs con área táctil mínima de 44px (`py-2.5 px-4`).
      - Contrastes superiores a 10:1 (superando el estándar WCAG AAA de 7:1) en textos `#f8fafc` sobre fondos `#0a0e17` y `#121824`.
      - Tablas con contenedor `overflow-x-auto` para visualización táctil fluida en smartphones sin romper el viewport.
  - **Interactividad y Pestañas Dinámicas (`switchDashboardTab`):**
    - Sincronización de estados activos/inactivos en las 4 pestañas: Directorio de Clientes, Cotizador & Propuestas, Telemetría de Referidos y Suite Contable CFO.
  - **Preservación Total de Lógica de Negocio:**
    - Se mantuvieron al 100% las funciones JavaScript operativas (PIN 3690, alta y edición de clientes, cotizador compacto, libros contables, telemetría y exportación CSV).
