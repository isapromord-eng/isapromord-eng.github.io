# 🤝 HANDOFF.md — Estado Técnico de IsaPromo RD (isapromord.com)

> **Nodo MBOS:** `isapromord.com`  
> **Última Actualización:** 2026-10-01  
> **Repositorio Oficial:** [https://github.com/isapromord/isapromord.com](https://github.com/isapromord/isapromord.com)  
> **Repositorio Root Pages:** [https://github.com/isapromord/isapromord.github.io](https://github.com/isapromord/isapromord.github.io)  
> **URLs EN VIVO Y FUNCIONALES ($0 Costo):**  
> - 🌐 **Root Principal:** [https://isapromord.github.io/](https://isapromord.github.io/)  
> - 🌐 **Subpath:** [https://isapromord.github.io/isapromord.com/](https://isapromord.github.io/isapromord.com/)  
> - 🛡️ **Dashboard Administrador:** [https://isapromord.github.io/dashboard/](https://isapromord.github.io/dashboard/) (PIN predeterminado: `3690`)  
> **Estado del Sistema:** En línea, HTTPS activo, 100% operativo sin costo mensual. Primer cliente en producción: Pasión Pecuaria RD.

---

## 1. RESUMEN EJECUTIVO
- **Dominio Futuro:** `isapromord.com`
- **Dominio Actual en Vivo:** `https://isapromord.github.io/`
- **Dashboard de Clientes:** `/dashboard/` (protegido por PIN, con monitor de Uptime, gestión de cobros y generador de reportes WhatsApp).
- **Cotizador & Propuestas "A la Carte":** `/propuesta/` (sistema de propuestas interactivas digitales con cálculo reactivo en tiempo real y aprobación por WhatsApp).
- **Sistema de Referidos & Telemetría:** Pestaña 3 en `/dashboard/` y detector en `index.html` (`?ref=...`). Mide clics, atribución de leads por WhatsApp a 90 días, tabla de partners y generador de badges ("Powered by ISAPromoRD") en React JSX y HTML.
- **Catálogo Oficial de Servicios ISAPromoRD (Opción A):**
  1. 🌐 Landing Page Transaccional de Alta Conversión (<1s en React/Vite) — RD$ 20,000 / RD$ 4,500/mes
  2. 📍 Optimización Profesional de Google Maps (GBP) — RD$ 15,000 / RD$ 12,000/mes
  3. 🔍 Optimización GEO & Schemas para ChatGPT y Gemini — RD$ 15,000 único
  4. 💬 Chatbot Inteligente para Servicios e Inventario — RD$ 15,000 único
  5. 🤖 Agente de Inteligencia Artificial 24/7 (Citas & FAQ) — RD$ 25,000 / RD$ 10,000/mes
  6. 💼 CRM Personalizado a la Medida del Negocio — RD$ 35,000 / RD$ 8,000/mes
- **Paquetes Oficiales:**
  - P1: Presencia & Captación Local (Setup RD$ 30,000 / RD$ 15,000 mes)
  - P2 ⭐: Crecimiento & Control CRM [MÁS POPULAR] (Setup RD$ 65,000 / RD$ 20,000 mes)
  - P3: Negocio Inteligente con IA (Setup RD$ 50,000 / RD$ 20,000 mes)
  - P4: Ecosistema Digital Completo + CRM (Setup RD$ 85,000 / RD$ 30,000 mes)
- **Clientes en Producción:**
  - **Pasión Pecuaria RD:** `https://pasionpecuaria.vercel.app` (Repo oficial: `github.com/isapromord/pasion-pecuaria-rd` | React 18 + Vite + Tailwind CSS en Vercel Anycast | Ref slug: `pasionpecuaria`).
- **Usuario GitHub:** `isapromord`
- **Branch Principal:** `main`
- **Hosting Activo:** GitHub Pages CDN Anycast Global con SSL automático.
- **Estatus SEO:** Microdatos Schema.org integrados, geolocalización DO-01, `robots.txt` con restricción de `/dashboard/` y `/propuesta/`, y `sitemap.xml` canónico sincronizado.

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

*Nota: Una vez guardados los registros DNS, GitHub Pages activará automáticamente el certificado SSL (HTTPS) gratuito en unos minutos.*

---

## 3. CHECKLIST PARA GOOGLE SEARCH CONSOLE (GSC)

1. Ingresa a [Google Search Console](https://search.google.com/search-console/).
2. Haz clic en **Añadir Propiedad**:
   - **Opción Recomendada (Dominio):** Ingresa `isapromord.com`. Google te entregará un registro `TXT` (ej. `google-site-verification=...`). Agrégalo en tu panel de DNS con Host `@`.
   - **Opción Alternativa (Prefijo de URL):** Ingresa `https://isapromord.com`. Copia la etiqueta HTML `<meta name="google-site-verification" content="..." />` y reemplaza el token en `index.html`.
3. **Enviar Sitemap:**
   - Ve a la sección **Sitemaps** en el menú izquierdo de GSC.
   - Escribe `sitemap.xml` y haz clic en **Enviar**.
   - Google confirmará el rastreo inmediato del sitio.

---

## 4. CHECKLIST PARA GOOGLE BUSINESS PROFILE (GBP)

- Ficha oficial: **ISAPromoRD**
- Categoría Principal (Primary Category):
  - En inglés: **`Internet marketing service`** (Exacta)
  - En español: **`Agencia de marketing en Internet`**
- Categorías Secundarias (Additional Categories):
  - **`Website designer`** / *Diseñador de páginas web*
  - **`Marketing agency`** / *Agencia de marketing*
  - **`Marketing consultant`** / *Consultor de marketing*
- Dirección: **Santo Domingo, Distrito Nacional, República Dominicana**
- Sitio Web: `https://isapromord.com` (o mientras tanto `https://isapromord.github.io/`)
- WhatsApp/Teléfono: `+1 (829) 455-4783`
