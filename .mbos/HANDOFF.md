# 🤝 HANDOFF.md — Estado Técnico de IsaPromo RD (isapromord.com)

> **Nodo MBOS:** `isapromord.com`  
> **Última Actualización:** 2026-09-27  
> **Estado del Sistema:** Arquitectura y Assets reconstruidos. Listo para despliegue y configuración de Google Search Console.

---

## 1. RESUMEN EJECUTIVO
- **Dominio:** `isapromord.com`
- **Diagnóstico Previo:** Anteriormente hosteado en Netlify; el servicio expiró y fue removido. El proyecto está siendo re-diseñado y construido desde cero con un stack moderno, ultrarrápido y enfocado al 100% en dominancia de **SEO Local**, Google Business Profile, Schema.org estructurado y alta conversión móvil en República Dominicana.
- **Identidad Visual:** Logo 3D monitor + megáfono (`assets/logo.png`), paleta Indigo/Electric Blue (`#2563EB`) y Amber (`#F59E0B`), tipografía sans-serif de alta legibilidad, estética limpia tipo Stripe/Linear con fondo claro off-white.

---

## 2. ARQUITECTURA DE ARCHIVOS
- `assets/logo.png`: Logotipo oficial optimizado para web.
- `.mbos/BRAIN.md`: Filosofía, reglas inmutables de SEO Local y pilares de diseño.
- `.mbos/MEMORY.md`: Bitácora acumulativa append-only de decisiones técnicas.
- `.mbos/HANDOFF.md`: Este documento de entrega y estado de operaciones.
- `robots.txt`: Directivas de rastreo para Googlebot, Bingbot y validadores SEO.
- `sitemap.xml`: Mapa del sitio XML canónico con prioridad 1.0 para indexación inmediata.
- `index.html`: Landing page integral con Schema JSON-LD, Geo-Tags dominicanos, widget interactivo de auditoría SEO local, casos de éxito, acordeón FAQ y botón de WhatsApp dinámico.

---

## 3. CHECKLIST PARA GOOGLE SEARCH CONSOLE Y GOOGLE BUSINESS PROFILE
1. **DNS & Hosting:**
   - Apuntar el dominio `isapromord.com` a Cloudflare / Vercel / Netlify / Firebase.
2. **Google Search Console (GSC):**
   - Subir el registro TXT de verificación en el panel DNS del dominio, o activar mediante la meta etiqueta `<meta name="google-site-verification" content="..." />` provista en el `index.html`.
   - Enviar `https://isapromord.com/sitemap.xml` a Google Search Console.
3. **Google Business Profile (GBP):**
   - Verificar la ficha de Google Business con la misma información NAP:
     - **Nombre:** IsaPromo RD
     - **Categoría:** Agencia de marketing en internet / Consultor de SEO
     - **Dirección:** Santo Domingo, República Dominicana
     - **Teléfono:** Vinculado al canal oficial de WhatsApp
     - **Website:** `https://isapromord.com`
4. **Backlinks & Citaciones Locales en RD:**
   - Registrar la empresa en directorios locales dominicanos (Páginas Amarillas RD, Degusta, FindGlocal, Cámara de Comercio de Santo Domingo).

---

## 4. PRÓXIMOS PASOS
- [x] Crear estructura `.mbos/` y guardar branding.
- [x] Crear `robots.txt` y `sitemap.xml`.
- [x] Desarrollar `index.html` con microdatos Schema.org y componentes de alta conversión.
- [ ] Conectar dominio DNS y activar SSL.
- [ ] Verificar en Google Search Console y solicitar indexación prioritaria.
