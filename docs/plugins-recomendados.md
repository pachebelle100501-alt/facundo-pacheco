# Plugins recomendados de GitHub (por equipo)

Revisar el código antes de instalar. Instalar: `/plugin marketplace add <owner>/<repo>`.

## Para todos (eficiencia)
- mksglu/context-mode — saca la salida de las herramientas del contexto (ahorra tokens).
- JuliusBrussee/caveman — respuestas más cortas, menos tokens.
- OthmanAdi/planning-with-files — planes en archivos, retomables.
- jarrodwatts/claude-hud — muestra contexto y agentes activos.
- Dicklesworthstone/destructive_command_guard — bloquea comandos peligrosos.
- getagentseal/codeburn — mide tokens y costo.

## Web
- anthropics/claude-plugins-official — directorio oficial.
- Nutlope/hallmark — diseño sin estética "hecha por IA".

## Automatizaciones
- czlonkowski/n8n-skills — construir workflows n8n sin errores.
- EtienneLescot/n8n-as-code — 537 nodos con esquemas y 7.700+ plantillas.
- hookdeck/webhook-skills — integración de webhooks.

## Apps
- wshobson/agents — agentes especializados por stack.
- VoltAgent/awesome-claude-code-subagents — más de 100 subagentes.

## Video y foto
- kevinbadi/open-edits — edición de video con Claude Code.
- pycodebr/heditor — edición de video vertical.
- vargHQ/skills — 83 skills de video con IA.
- motiful/product-shots — de una foto de producto a un set completo de e-commerce.

## Redes
- coreyhaines31/marketingskills — CRO, copy, SEO, growth.
- thatrebeccarae/claude-marketing — Klaviyo, Shopify, GA4.

## Dropshipping
- vargHQ/ecommerce-ai-video-skills — 10 formatos de video para anuncios.
- Lifecycle-Innovations-Limited/claude-ops — sistema operativo de negocio.
- noique/cross-border-ecommerce-skills — 58 skills de e-commerce internacional (en chino).

## Estado de instalación
**Activados en `.claude/settings.json`** (se instalan solos al abrir el repo en Claude Code y aceptar la confianza de la carpeta):
context-mode, planning-with-files, codeburn, hallmark, n8n-mcp-skills, marketing-skills y, de webhook-skills: patrones generales, Shopify, Stripe, PayPal, n8n, WhatsApp, Instagram y TikTok Shop.

**Copiados en `.claude/skills/`** (licencia MIT, origen en cada `ORIGEN.md`): heditor, product-shots (7 skills) y open-edits (6 skills).

**No instalados:**
- claude-hud y vargHQ/skills: no pasan la validación de plugins de Claude Code.
- caveman: deforma la redacción y perjudica los textos para clientes y redes.
- destructive_command_guard: es un binario en Rust, no un plugin.
- ecommerce-ai-video-skills: es una guía, sin skills instalables.

## Limpieza 2026-11-27
**Plugins de cuenta a quitar** (fuera de las áreas del estudio o con conectores que fallan): bio-research, unity, unreal-engine, meshy-3d-agent, cfdagent, sp-global, finance, legal, human-resources, zoom-plugin, sales, apollo, customer-support, enterprise-search, operations, product-management, data, wordpress-mcp, imessage.

**Duplicados**: SEO queda solo `searchfit-seo` (fuera `rampstack-seo` y `marketing`). Diseño web queda `frontend-design` + `website-design` (fuera `superdesign` y `design`). Cloudflare y Netlify se usan como conector, no como plugin.

**Conectores**: fuera Expedia, Trivago, OnChainDiligence, ThunderPhone; elegir uno entre Evernote/Notion, Asana/monday.com y Microsoft 365/Google.
