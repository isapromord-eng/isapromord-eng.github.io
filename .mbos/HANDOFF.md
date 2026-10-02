# 🤝 HANDOFF.md — Estado Técnico de IsaPromo RD (isapromord.com)

> **Nodo MBOS:** `isapromord.com`  
> **Última Actualización:** 2026-10-02  
> **Repositorio Oficial:** [https://github.com/isapromord/isapromord.com](https://github.com/isapromord/isapromord.com)  
> **Repositorio Root Pages:** [https://github.com/isapromord/isapromord.github.io](https://github.com/isapromord/isapromord.github.io)  
> **URLs EN VIVO Y FUNCIONALES ($0 Costo):**  
> - 🌐 **Root Principal:** [https://isapromord.github.io/](https://isapromord.github.io/)  
> - 🛡️ **Dashboard Administrador:** [https://isapromord.github.io/dashboard/](https://isapromord.github.io/dashboard/) (PIN: `3690`)  
> - 📄 **Propuesta Pasión Pecuaria (Ruta Limpia):** [https://isapromord.github.io/propuestas/pasionpecuaria/](https://isapromord.github.io/propuestas/pasionpecuaria/)  
> - 📄 **Motor de Propuestas Dinámicas:** [https://isapromord.github.io/propuesta/](https://isapromord.github.io/propuesta/)  
> **Estado del Sistema:** En línea, HTTPS activo, 100% operativo sin costo mensual. Primer cliente en producción: Pasión Pecuaria RD.

---

## 1. RESUMEN EJECUTIVO
- **Dominio Futuro:** `isapromord.com` (se activará cuando el usuario adquiera el dominio).
- **Dominio Actual en Vivo:** `https://isapromord.github.io/`
- **Dashboard de Clientes:** `/dashboard/` (protegido por PIN `3690`).
- **Sistema de Facturación Recurrente & Retainers Mensuales (Industry Standard):**
  - **Semáforo de Ciclo en Tarjeta de Cliente:** `🟢 Al Día` (>5 días), `🟡 Por Vencer` (<=5 días), `🔴 Vencido` (muestra días de mora).
  - **Aviso de Cobro & Renovación por WhatsApp (1 Clic):** Modal que compila estado de cuenta formal con período, servicios cubiertos y datos bancarios para transferencia (Banco Popular Dominicano).
  - **Registro de Pago con 1 Clic (`✓ Pagado`):** Extiende automáticamente la fecha de renovación al mes siguiente (+1 mes), asienta el recibo en el historial interno de pagos y registra la tarea en la bitácora del cliente.
  - **Ajustes de Cuentas Bancarias:** Configurable en el modal de Ajustes & Respaldo (`backupModal`) y guardado en `localStorage`.
- **Arquitectura de URLs de Marca y Enrutamiento Limpio:**
  - **Ruta Fija Personalizada para Pasión Pecuaria RD:** `https://isapromord.github.io/propuestas/pasionpecuaria/` (Directorio y archivo físico en el repositorio, cero parámetros, carga instantánea).
  - **Ruta Dinámica para Nuevos Clientes:** `https://isapromord.github.io/propuesta/?cliente=Nombre&plan=crm` (~60 caracteres, completamente legible).
  - **Descarga Directa de PDF:** `https://isapromord.github.io/propuestas/pasionpecuaria/?download=1`
- **Integración de WhatsApp Directo al Cliente:**
  - El formulario del Dashboard incluye el campo interactivo **"WhatsApp del Cliente (Para Enviar)"**, auto-completado con los datos del cliente registrado.
  - Al generar la propuesta, el botón "WhatsApp" enlaza directamente con el número del cliente (`https://wa.me/1829XXXXXXX?text=...`), evitando que el remitente se abra el chat consigo mismo.
- **Protección Anti-Caché:**
  - Cabeceras `Cache-Control: no-cache, no-store, must-revalidate` inyectadas en `<head>` para garantizar que las actualizaciones en producción se reflejen de inmediato.
- **Jerarquía Comercial en Dashboard (`/dashboard/`):**
  - **Paso 1: Paquetes Comerciales Recomendados:** Visible en primera plana con las 5 opciones: Crecimiento CRM (⭐ Más Popular), Presencia Local (Esencial), Automatización IA, Ecosistema Total y 100% A la Carta.
  - **Paso 2: Servicios y Módulos de la Propuesta (A la Carta):** Selección granular con insignias visuales `✓ En Combo` y subtotal reactivo.
  - **Paso 3: Tablero de Análisis Comparativo en Vivo:** Muestra simultáneamente Total A la Carta, Inversión en Paquete y Ahorro Inmediato Demostrado ("🔥 Te ahorras RD$ X en Setup").
  - **Modal de Salida:** Proporciona enlace web interactivo corto, botón para descargar directamente el archivo físico `.pdf` y botón de WhatsApp directo al cliente.
- **Experiencia del Cliente en Propuestas (`/propuesta/`):**
  - **Terminología Ejecutiva Limpia:** Lenguaje corporativo ("Máxima Visibilidad Local & Nuevos Clientes en Google", "Llamadas & WhatsApp Directo").
  - **Descarga Directa de PDF (`html2pdf.js`):** Genera y descarga automáticamente el archivo físico `Propuesta_ISAPromoRD_[Cliente].pdf` en formato A4 de alta resolución con membrete corporativo blanco y sección formal de firmas.
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
  - **Pasión Pecuaria RD:** `https://pasionpecuaria.vercel.app` (Tel/WA: `+1 (829) 396-1318` | Email: `pasionpecuariard@gmail.com` | Repo oficial: `github.com/isapromord/pasion-pecuaria-rd` | React 18 + Vite + Tailwind CSS en Vercel Anycast | Ref slug: `pasionpecuaria`).
- **Branch Principal:** `main`
- **Hosting Activo:** GitHub Pages CDN Anycast Global con SSL automático.
