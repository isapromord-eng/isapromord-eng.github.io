# 🤝 HANDOFF.md — Estado Técnico de IsaPromo RD (isapromord.com)

> **Nodo MBOS:** `isapromord.com`  
> **Última Actualización:** 2026-10-01  
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
- **Cotizador & Propuestas de Alto Valor:** `/propuesta/` (sistema de propuestas interactivas digitales con comparativa en vivo "A la Carta vs Paquete Combo", cálculo de ahorro demostrado, aprobación por WhatsApp y exportación a PDF formal).
- **Arquitectura de la Propuesta Comercial en Dashboard (`/dashboard/`):**
  - **Paso 1: Módulos Solicitados "A la Carta":** Selección sin restricciones de cualquiera de los 10 módulos de software, IA y SEO local con subtotal reactivo.
  - **Paso 2: Paquete Recomendado a Ofrecer:** Selector de combos (sugiere por defecto `pack-crm` o permite seleccionar "Sin Paquete / Solo A la Carta").
  - **Paso 3: Caja de Análisis Comparativo en Vivo:** Muestra simultáneamente el Total A la Carta, Inversión en Paquete y Ahorro Inmediato Demostrado ("🔥 Te ahorras RD$ X en Setup").
  - **Modal de Salida:** Proporciona enlace web interactivo, botón directo para guardar en PDF con auto-impresión (`?print=1`) y enlace para redactar el mensaje de WhatsApp.
- **Experiencia del Cliente en Propuestas (`/propuesta/`):**
  - **Comparativa Lado a Lado:** Tarjeta 1 (Servicios A la Carta) vs Tarjeta 2 (Paquete Recomendado con banner de ahorro destacado).
  - **Interactividad:** El cliente puede hacer clic en cualquiera de las dos tarjetas para seleccionarla, recalculando la barra inferior y configurando el mensaje de WhatsApp respectivo.
  - **Exportación en PDF / Impresión:** Cabecera con botón "Descargar en PDF", soporte `@media print`, membrete corporativo oficial y caja de firmas para autorización formal de inicio.
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

---

## 2. CONFIGURACIÓN DE DNS PARA ACTIVAR `isapromord.com`

En tu registrador de dominio (Namecheap, GoDaddy, Cloudflare, etc.), agrega estos registros DNS:

### A. Registros A (Para el dominio raíz `isapromord.com`):
| Tipo | Nombre / Host | Valor / Dirección IP | TTL |
| :--- | :--- | :--- | :--- |
| **A** | `@` (o en blanco) | `185.199.108.153` | Automático / 3600 |
| **A** | `@` (o en blanco) | `185.199.109.153` | Automático / 3600 |
| **A** | `@` (o en blanco) | `185.199.110.153` | Automático / 3600 |
| **A** | `@` (o en blanco) | `185.199.111.153` | Automático / 3600 |

### B. Registro CNAME (Para el subdominio `www`):
| Tipo | Nombre / Host | Valor / Destino | TTL |
| :--- | :--- | :--- | :--- |
| **CNAME** | `www` | `isapromord.github.io` | Automático / 3600 |

---

## 3. CHECKLIST PARA GOOGLE SEARCH CONSOLE (GSC)

1. Ingresa a [Google Search Console](https://search.google.com/search-console/).
2. Haz clic en **Añadir Propiedad**:
   - **Opción Recomendada (Dominio):** Ingresa `isapromord.com`. Google te entregará un registro `TXT` (ej. `google-site-verification=...`). Agrégalo en tu panel de DNS con Host `@`.
3. **Enviar Sitemap:**
   - Ve a la sección **Sitemaps** en el menú izquierdo de GSC.
   - Escribe `sitemap.xml` y haz clic en **Enviar**.

---

## 4. CHECKLIST PARA GOOGLE BUSINESS PROFILE (GBP)

- Ficha oficial: **ISAPromoRD**
- Categoría Principal: **`Internet marketing service`** / **`Agencia de marketing en Internet`**
- Categorías Secundarias: **`Website designer`**, **`Marketing agency`**, **`Marketing consultant`**
- Dirección: **Santo Domingo, Distrito Nacional, República Dominicana**
- Sitio Web: `https://isapromord.com` (o `https://isapromord.github.io/`)
- WhatsApp/Teléfono: `+1 (829) 455-4783`
