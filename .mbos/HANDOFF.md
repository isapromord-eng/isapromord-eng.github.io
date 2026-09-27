# 🤝 HANDOFF.md — Estado Técnico de IsaPromo RD (isapromord.com)

> **Nodo MBOS:** `isapromord.com`  
> **Última Actualización:** 2026-09-27  
> **Repositorio Oficial:** [https://github.com/isapromord-eng/isapromord.com](https://github.com/isapromord-eng/isapromord.com)  
> **Estado del Sistema:** Repositorio en GitHub creado, GitHub Pages activo con CNAME configurado. Listo para apuntar DNS y verificar en Google Search Console.

---

## 1. RESUMEN EJECUTIVO
- **Dominio:** `isapromord.com`
- **Organización GitHub:** `isapromord-eng/isapromord.com` (Público)
- **Branch Principal:** `main`
- **Hosting Activo:** GitHub Pages con CDN global y soporte para dominio personalizado `isapromord.com`.
- **Estatus SEO:** Microdatos Schema.org integrados, geolocalización DO-01, `robots.txt` y `sitemap.xml` sincronizados.

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
| **CNAME** | `www` | `isapromord-eng.github.io` | Automático / 3600 |

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

- Ficha oficial: **IsaPromo RD**
- Categoría: **Agencia de marketing en Internet** / **Consultor de SEO**
- Dirección: **Santo Domingo, Distrito Nacional, República Dominicana**
- Sitio Web: `https://isapromord.com`
- WhatsApp/Teléfono: `+1 (829) 555-0199`
