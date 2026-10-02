# 🤝 HANDOFF.md — Estado Técnico de IsaPromo RD (isapromord.com)

> **Nodo MBOS:** `isapromord.com`  
> **Última Actualización:** 2026-10-02  
> **Repositorio Oficial:** [https://github.com/isapromord/isapromord.com](https://github.com/isapromord/isapromord.com)  
> **Repositorio Root Pages:** [https://github.com/isapromord/isapromord.github.io](https://github.com/isapromord/isapromord.github.io)  
> **URLs EN VIVO Y FUNCIONALES ($0 Costo):**  
> - 🌐 **Root Principal:** [https://isapromord.github.io/](https://isapromord.github.io/)  
> - 🌐 **Subpath:** [https://isapromord.github.io/isapromord.com/](https://isapromord.github.io/isapromord.com/)  
> - 🛡️ **Dashboard Administrador:** [https://isapromord.github.io/dashboard/](https://isapromord.github.io/dashboard/) (PIN predeterminado: `3690`)  
> - 📄 **Propuestas Digitales:** [https://isapromord.github.io/propuesta/](https://isapromord.github.io/propuesta/)  
> **Estado del Sistema:** En línea, HTTPS activo, 100% operativo sin costo mensual. Primer cliente en producción: Pasión Pecuaria RD.

---

## 1. RESUMEN EJECUTIVO
- **Dominio Futuro:** `isapromord.com`
- **Dominio Actual en Vivo:** `https://isapromord.github.io/`
- **Dashboard de Clientes:** `/dashboard/` (protegido por PIN, con monitor de Uptime, gestión de cobros y generador de reportes WhatsApp).
- **Cotizador & Propuestas de Alto Valor:** `/propuesta/` (sistema de propuestas interactivas digitales con comparativa en vivo "A la Carta vs Paquete Combo", cálculo de ahorro demostrado, aprobación por WhatsApp y exportación directa de archivo PDF).
- **Arquitectura de URLs Compactas (Solución HTTP 414):**
  - Se eliminó la serialización masiva Base64 de la URL (`?d=...`) que generaba error 414 URI Too Long.
  - La URL generada ahora es limpia, profesional y ultracorta (~180 caracteres) con parámetros semánticos: `?id=...&client=...&cat=...&pkg=...&svc=...&mode=...`.
  - `/propuesta/` cuenta con catálogos locales completos (`SERVICE_CATALOG` y `PACKAGE_CATALOG`) con títulos, descripciones completas y entregables oficiales para reconstruir reactivamente la propuesta en cualquier dispositivo.
  - Soporte de caché en `localStorage` con clave `proposal_{id}` para renderizado inmediato en el dashboard y compatibilidad hacia atrás con el parámetro legacy `?d=`.
- **Jerarquía Comercial en Dashboard (`/dashboard/`):**
  - **Paso 1: Paquetes Comerciales Recomendados:** Visible en primera plana con las 5 opciones: Crecimiento CRM (⭐ Más Popular), Presencia Local (Esencial), Automatización IA, Ecosistema Total y 100% A la Carta.
  - **Paso 2: Servicios y Módulos de la Propuesta (A la Carta):** Selección granular con insignias visuales `✓ En Combo` y subtotal reactivo.
  - **Paso 3: Tablero de Análisis Comparativo en Vivo:** Muestra simultáneamente Total A la Carta, Inversión en Paquete y Ahorro Inmediato Demostrado ("🔥 Te ahorras RD$ X en Setup").
  - **Modal de Salida:** Proporciona enlace web interactivo, botón para descargar directamente el archivo físico `.pdf` (`&download=1`) y enlace de WhatsApp formateado.
- **Experiencia del Cliente en Propuestas (`/propuesta/`):**
  - **Terminología Ejecutiva Limpia:** Reemplazados todos los tecnicismos extraños por lenguaje corporativo ("Máxima Visibilidad Local & Nuevos Clientes en Google", "Llamadas & WhatsApp Directo").
  - **Descarga Directa de PDF (`html2pdf.js`):** El botón "Descargar en PDF" (o el enlace con `&download=1`) genera y descarga automáticamente el archivo físico `Propuesta_ISAPromoRD_[Cliente].pdf` en formato A4 de alta resolución con membrete corporativo y sección de firmas.
  - **Estilos de Impresión / PDF:** Sin fondo negro ni consumo excesivo de tinta; membrete corporativo blanco ejecutivo con caja formal de firmas y autorización de inicio.
- **Sistema de Referidos & Telemetría:** Pestaña 3 en `/dashboard/` y detector en `index.html` (`?ref=...`). Mide clics, atribución de leads por WhatsApp a 90 días, tabla de partners y generador de badges ("Powered by ISAPromoRD") en React JSX y HTML.
- **Catálogo Oficial de Servicios ISAPromoRD (Opción A):**
  1. 🌐 Landing Page Transaccional de Alta Conversión (<1s en React/Vite) — RD$ 20,000 / RD$ 4,500/mes
  2. 📍 Optimización Profesional de Google Maps (GBP) — RD$ 15,000 / RD$ 12,000/mes
  3. 🔍 Optimización GEO & Schemas para ChatGPT y Gemini — RD$ 15,000 único
  4. 💬 Chatbot Inteligente para Servicios e Inventario — RD$ 15,000 único
  5. 🤖 Agente de Inteligencia Artificial 24/7 (Citas & FAQ) — RD$ 25,000 / RD$ 10,000/mes
  6. 💼 CRM Personalizado a la Medida del Negocio — RD$ 35,000 / RD$ 8,000/mes
- **Paquetes Oficiales:**
  - P0: Sin Paquete Base / 100% A la Carta (RD$ 0 base / cálculo según selección)
  - P1: Presencia & Captación Local (Setup RD$ 30,000 / RD$ 15,000 mes)
  - P2 ⭐: Crecimiento & Control CRM [MÁS POPULAR] (Setup RD$ 65,000 / RD$ 20,000 mes)
  - P3: Negocio Inteligente con IA (Setup RD$ 50,000 / RD$ 20,000 mes)
  - P4: Ecosistema Digital Completo + CRM (Setup RD$ 85,000 / RD$ 30,000 mes)
- **Clientes en Producción:**
  - **Pasión Pecuaria RD:** `https://pasionpecuaria.vercel.app` (Repo oficial: `github.com/isapromord/pasion-pecuaria-rd` | React 18 + Vite + Tailwind CSS en Vercel Anycast | Ref slug: `pasionpecuaria`).
- **Branch Principal:** `main`
- **Hosting Activo:** GitHub Pages CDN Anycast Global con SSL automático.
