# 🏆 Claude Code Best Repositories

Una colección curada de los mejores repositorios de skills, plugins y recursos para **Claude Code**.

> **Mantenido por:** [@MarioMaldonadoH](https://github.com/MarioMaldonadoH)
> **Última actualización:** Marzo 2026

---

## 🛡️ Sistema de Auditoría de Seguridad

Esta lista incluye verificación de seguridad activa usando **[trailofbits/skills](https://github.com/trailofbits/skills)** como herramienta de auditoría. Cada repo fue analizado con agentes especializados que revisaron: transmisión de datos a servidores externos, ejecución de código de terceros sin verificación de integridad, credenciales hardcodeadas, y hooks que intercepten conversaciones de Claude.

**✅ Todos los repos de esta lista han sido auditados.**

### Leyenda

| Badge | Significado |
|-------|-------------|
| ✅ **AUDITADO · SEGURO** | Analizado — sin riesgos significativos. Instalar con confianza. |
| ⚠️ **CONDICIONAL** | Riesgos identificados. Instalar solo siguiendo las instrucciones de mitigación. |
| 🚨 **NO INSTALAR** | Vulnerabilidad grave confirmada. Solo si asumes el riesgo explícitamente. |

---

## 📌 Índice

- [🥇 Top Esenciales](#-top-esenciales)
- [📚 Colecciones Curadas](#-colecciones-curadas)
- [🛠️ Frameworks y Herramientas](#-frameworks-y-herramientas)
- [🎯 Skills Especializadas](#-skills-especializadas)
- [💼 Marketing y Ventas](#-marketing-y-ventas)
- [🔒 Seguridad](#-seguridad)
- [⚠️ Instalación Condicional](#-instalación-condicional)
- [🚨 No Instalar Sin Mitigación](#-no-instalar-sin-mitigación)

---

## 🥇 Top Esenciales

| Repositorio | Estrellas | Seguridad | Descripción |
|-------------|-----------|-----------|-------------|
| **[everything-claude-code](https://github.com/affaan-m/everything-claude-code)** | 73.3k ⭐ | ✅ SEGURO | Framework completo de optimización. `install.sh` solo copia archivos localmente, sin requests de red. MIT. |
| **[claude-plugins-official](https://github.com/anthropics/claude-plugins-official)** | 10.1k ⭐ | ✅ OFICIAL ANTHROPIC | Directorio de plugins gestionado por el equipo oficial de Anthropic. |

---

## 📚 Colecciones Curadas

> Estas son listas de recursos, no instalan código. Su contenido es markdown puro. Riesgo: los repos a los que apuntan no están auditados individualmente.

| Repositorio | Estrellas | Seguridad | Descripción |
|-------------|-----------|-----------|-------------|
| **[awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code)** | 27.7k ⭐ | ✅ SEGURO · LOW | Lista curada de skills, hooks, slash-commands y plugins. CC BY-NC-ND 4.0. Sin código ejecutable. |
| **[awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills)** | 11.0k ⭐ | ✅ SEGURO · LOW | 500+ skills de agentes compatibles. Solo 3 archivos markdown. MIT. |
| **[awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills)** | 8.7k ⭐ | ✅ SEGURO · LOW | Recursos para personalizar flujos de Claude. Sin código ejecutable. Sin licencia declarada — riesgo legal, no de seguridad. |

---

## 🛠️ Frameworks y Herramientas

| Repositorio | Estrellas | Seguridad | Descripción |
|-------------|-----------|-----------|-------------|
| **[AionUi](https://github.com/iOfficeAI/AionUi)** | 18.6k ⭐ | ✅ SEGURO · LOW | App desktop open-source para múltiples asistentes IA. Auto-updater estándar desde GitHub releases. API keys en SQLite local. Apache 2.0. Modo remoto requiere TLS externo. |
| **[refly](https://github.com/refly-ai/refly)** | 7.0k ⭐ | ⚠️ CONDICIONAL · MEDIUM | Ver [sección Condicional](#refly-aireflycondicional-medium) |
| **[cc-switch](https://github.com/farion1231/cc-switch)** | 27.3k ⭐ | ⚠️ CONDICIONAL · MEDIUM | Ver [sección Condicional](#farion1231cc-switchcondicional-medium) |
| **[claude-code-infrastructure-showcase](https://github.com/diet103/claude-code-infrastructure-showcase)** | 9.2k ⭐ | ⚠️ CONDICIONAL · HIGH | Ver [sección Condicional](#diet103claude-code-infrastructure-showcasecondicional-high) |
| **[claude-code-showcase](https://github.com/ChrisWiles/claude-code-showcase)** | 5.5k ⭐ | ⚠️ CONDICIONAL · LOW | Ver [sección Condicional](#chriswilesclaude-code-showcasecondicional-low) |
| ~~**[gstack](https://github.com/garrytan/gstack)**~~ | 4.2k ⭐ | 🚨 NO INSTALAR | Ver [sección No Instalar](#garrytan-gstack) |

---

## 🎯 Skills Especializadas

| Repositorio | Estrellas | Seguridad | Descripción |
|-------------|-----------|-----------|-------------|
| **[planning-with-files](https://github.com/OthmanAdi/planning-with-files)** | 15.9k ⭐ | ✅ SEGURO | Planificación persistente estilo Manus. Sin exfiltración. Hook PreToolUse de amplio alcance (benigno). MIT. |
| **[humanizer](https://github.com/blader/humanizer)** | 8.8k ⭐ | ✅ SEGURO · LOW | Solo 3 archivos Markdown, cero código ejecutable. Sin licencia — riesgo legal menor. |
| **[claude-skills (Jeffallan)](https://github.com/Jeffallan/claude-skills)** | 6.4k ⭐ | ✅ SEGURO · LOW | 66 skills para Full-Stack. Scripts de validación solo locales. Sin dependencias externas. MIT. |
| **[claude-skills (alirezarezvani)](https://github.com/alirezarezvani/claude-skills)** | 4.5k ⭐ | ✅ SEGURO · LOW | 180+ skills para Claude Code, Codex, OpenClaw. `install.sh` 100% local. Principio documentado: sin API keys de pago. MIT. |
| **[notebooklm-py](https://github.com/teng-lin/notebooklm-py)** | 5.3k ⭐ | ✅ SEGURO · LOW | Librería Python para automatizar NotebookLM. Solo comunica con `notebooklm.google.com`. Cookies de Google en `~/.notebooklm/` con permisos `0o600`. MIT. |
| **[AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs)** | 4.8k ⭐ | ⚠️ CONDICIONAL · MEDIUM | Ver [sección Condicional](#orchestra-researchai-research-skillscondicional-medium) |
| **[marketingskills](https://github.com/coreyhaines31/marketingskills)** | 13.0k ⭐ | ⚠️ CONDICIONAL · MEDIUM | Ver [sección Condicional](#coreyhaines31marketingskillscondicional-medium) |
| **[ai-marketing-claude](https://github.com/zubair-trabzada/ai-marketing-claude)** | 396 ⭐ | ⚠️ CONDICIONAL · MEDIUM | Ver [sección Condicional](#zubair-trabzadaai-marketing-claudecondicional-medium) |

---

## 💼 Marketing y Ventas

| Repositorio | Estrellas | Seguridad | License | Descripción |
|-------------|-----------|-----------|---------|-------------|
| **[email-marketing-bible](https://github.com/CosmoBlk/email-marketing-bible)** | 56 ⭐ | ✅ SEGURO | MIT | 55K palabras, 908 fuentes, 19 playbooks. Solo markdown, sin código ejecutable. Menciona "Nitrosend" (del autor) — publicidad implícita, no riesgo. |
| **[marketing-skills](https://github.com/kostja94/marketing-skills)** | 181 ⭐ | ✅ SEGURO · LOW | MIT | 160+ skills en markdown: SEO, ads, content marketing. Sin scripts de instalación propios. Método `npx skills add` depende de paquete npm `skills` externo — auditar ese paquete por separado si se usa ese método. |
| ~~**[ai-workflow](https://github.com/nicepkg/ai-workflow)**~~ | 131 ⭐ | 🚨 NO INSTALAR | MIT | Ver [sección No Instalar](#nicepkgai-workflow) |

---

## 🔒 Seguridad

| Repositorio | Estrellas | Seguridad | Descripción |
|-------------|-----------|-----------|-------------|
| **[skills](https://github.com/trailofbits/skills)** | 3.5k ⭐ | ✅ SEGURO | **Trail of Bits** — 35 plugins de auditoría: CodeQL, Semgrep, Semgrep, static analysis, supply chain auditing. Usado como herramienta de auditoría de esta lista. Instalar: `/plugin marketplace add trailofbits/skills` |

---

## ⚠️ Instalación Condicional

> Riesgos identificados. **Se pueden usar** siguiendo exactamente las instrucciones de mitigación.

---

### `refly-ai/refly` — CONDICIONAL · MEDIUM

**Riesgos identificados:**
- **[MEDIUM]** Licencia **no es Apache 2.0 pura**: contiene restricciones comerciales. Uso por empresas/organizaciones requiere licencia comercial. El productor puede endurecer términos unilateralmente.
- **[MEDIUM]** Un log de sesión de Claude Code fue accidentalmente commiteado al repo público (`.txt` en raíz). Revela arquitectura interna del equipo.
- **[MEDIUM]** Self-hosting requiere configurar: PostgreSQL, Redis, Qdrant, Elasticsearch, MinIO, Stripe, Resend, Langfuse, Sentry, Statsig, Composio. En modo cloud, datos pasan por todos estos servicios.

**Para usar de forma segura:**
```bash
# Self-hosting: usar DEPLOY_TYPE=self-hosted
DEPLOY_TYPE=self-hosted

# Deshabilitar telemetría — no configurar estas variables:
# STATSIG_SECRET_KEY, SENTRY_DSN, LANGFUSE_*

# Leer la licencia completa antes de uso comercial
cat LICENSE
```

---

### `farion1231/cc-switch` — CONDICIONAL · MEDIUM

**Riesgos identificados:**
- **[HIGH]** Actúa como **proxy local** que intercepta TODAS las llamadas a la API de Claude/Codex/Gemini. Todo el contenido de conversaciones pasa por este proceso local.
- **[MEDIUM]** API keys almacenadas en SQLite **sin cifrado en reposo** — solo enmascaradas en logs.
- **[MEDIUM]** Sincronización WebDAV puede transmitir la base de datos completa (con API keys) a servidor configurado por el usuario.
- **[MEDIUM]** Sponsoreado por servicios de relay de API de terceros — la app facilita redirigir tráfico a proveedores alternativos no oficiales.

**Para usar de forma segura:**
```bash
# Verificar que solo conecta a endpoints oficiales:
# api.anthropic.com, api.openai.com, generativelanguage.googleapis.com

# NO configurar WebDAV a menos que sea un servidor de tu control con HTTPS

# NO configurar providers de relay de terceros (PackyCode, AICodeMirror, etc.)

# Compilar desde source para verificar que el binario corresponde al código:
# cargo build --release (requiere Rust + Node)
```

---

### `diet103/claude-code-infrastructure-showcase` — CONDICIONAL · HIGH

**Riesgos identificados:**
- **[HIGH]** Hook `UserPromptSubmit` intercepta **todos los prompts** antes de que Claude responda. El código actual hace keyword matching local — benigno, pero el patrón es idéntico al de un keylogger.
- **[HIGH]** `settings.json` configura `"defaultMode": "acceptEdits"` con `Bash:*` sin restricción — Claude ejecuta cualquier cosa sin confirmación.
- **[MEDIUM]** `trigger-build-resolver.sh` auto-invoca Claude dentro de un hook de Claude — puede crear bucles recursivos.
- **[MEDIUM]** `eval` con paths de usuario en `tsc-check.sh` — vector de command injection si una ruta contiene metacaracteres shell.
- **[LOW]** `settings.local.json` commiteado al repo público.

**Para usar de forma segura:**
```bash
# NUNCA copiar settings.json completo — revisar item por item
# Eliminar obligatoriamente:
# "defaultMode": "acceptEdits"

# Copiar solo los hooks que necesitas, uno por uno, auditando cada script
# Verificar que ningún hook tiene curl, wget, fetch o sockets

# NO usar en máquinas de producción — es un repo educativo/referencia
```

---

### `ChrisWiles/claude-code-showcase` — CONDICIONAL · LOW

**Riesgos identificados:**
- **[LOW]** Hook `UserPromptSubmit` intercepta todos los prompts localmente para hacer keyword matching. Código auditable y benigno, sin exfiltración.
- **[LOW]** `.mcp.json` configura 8 servidores MCP (`jira`, `github`, `slack`, `postgres`, etc.) con `npx -y` — instala paquetes sin confirmación en runtime.
- **[LOW]** Sin licencia declarada.

**Para usar de forma segura:**
```bash
# Revisar .mcp.json y activar SOLO los MCP que realmente uses
# Auditar skill-eval.ts antes de instalar el hook
# Solicitar licencia al autor si usas en proyecto comercial
```

---

### `coreyhaines31/marketingskills` — CONDICIONAL · MEDIUM

**Riesgos identificados:**
- **[MEDIUM]** `validate-skills-official.sh` clona y ejecuta código de `agentskills/agentskills` (organización diferente, sin pinning de SHA).
- **[MEDIUM]** `AGENTS.md` instruye a Claude a hacer fetch autónomo de GitHub en cada primera sesión y ejecutar `git pull` sin solicitud explícita del usuario.

**Para instalar de forma segura (solo los .md de skills):**
```bash
git clone https://github.com/coreyhaines31/marketingskills
cp -r marketingskills/skills ~/.claude/skills/marketingskills/
# NUNCA ejecutar validate-skills-official.sh
# NO copiar AGENTS.md al proyecto
```

---

### `Orchestra-Research/AI-Research-SKILLs` — CONDICIONAL · MEDIUM

**Riesgos identificados:**
- **[MEDIUM]** CI/CD del repo upstream sube skills a API externa de Orchestra (`$ORCHESTRA_API_URL`) en cada push al repo original. No afecta clones propios.

**Para instalar de forma segura:**
```bash
git clone https://github.com/Orchestra-Research/AI-Research-SKILLs
cp -r AI-Research-SKILLs/skills/ ~/.claude/skills/ai-research/
# NUNCA configurar ORCHESTRA_API_URL ni ORCHESTRA_SYNC_API_KEY en tu fork
# NO instalar el paquete npm @orchestra-research/ai-research-skills
```

---

### `zubair-trabzada/ai-marketing-claude` — CONDICIONAL · MEDIUM

**Riesgos identificados:**
- **[MEDIUM]** Script de instalación detectable mediante `curl | bash` — clona repo completo antes de copiar archivos, sin verificación de integridad.
- **[MEDIUM]** Scripts Python hacen `urllib.request.urlopen()` a URLs sin validar esquema (potencial SSRF).
- **[LOW]** `requirements.txt` no pina versión exacta de `reportlab`.

**Para instalar de forma segura:**
```bash
# Clonar primero, inspeccionar, NUNCA usar curl | bash
git clone https://github.com/zubair-trabzada/ai-marketing-claude
# Revisar install.sh antes de ejecutar
bash install.sh

# Pinar dependencias:
# Cambiar "reportlab>=4.0" por "reportlab==X.Y.Z" en requirements.txt
```

---

### `ComposioHQ/awesome-claude-skills` — CONDICIONAL · HIGH

**Riesgos identificados:**
- **[CRÍTICO]** La skill `developer-growth-analysis` lee `~/.claude/history.jsonl` (historial completo de conversaciones con Claude — código propietario, secretos, contexto privado) y lo envía vía Composio a Slack.
- **[ALTO]** `connect-apps-plugin` escribe tu API key de Composio en `~/.mcp.json` en texto plano y establece canal permanente a servidores de Composio.
- **[MEDIO]** 100+ skills enrutan todo el tráfico de automatización (Gmail, Slack, GitHub, Stripe) a través de infraestructura de Composio.

**Si decides usarlo:**
```bash
# NUNCA instalar la skill developer-growth-analysis
# NUNCA usar connect-apps-plugin en máquinas con información sensible
# Revisar cada skill individualmente antes de instalar
# Asumir que cualquier acción automatizada (emails, issues) pasa por servidores de Composio
```

---

## 🚨 No Instalar Sin Mitigación

> Vulnerabilidades graves confirmadas. Solo instalar si comprendes y aceptas explícitamente cada riesgo.

---

### `garrytan/gstack`

**Vulnerabilidades:**
- **[HIGH]** Descifra cookies reales de Chrome/Brave/Edge/Arc (sesiones bancarias, GitHub, Google) y las pone bajo control de Claude.
- **[MEDIUM]** Ruta `/cookie-picker` sin autenticación — cualquier proceso local puede secuestrar la sesión.
- **[MEDIUM]** Instalación vía `curl | bash` sin checksum. Descarga ~130MB de Chromium sin hash verification.
- **[LOW]** Modifica `~/.claude/CLAUDE.md` global basándose en instrucciones del README del repo.

---

### `nicepkg/ai-workflow`

**Vulnerabilidades:**
- **[HIGH]** `tarfile.extractall()` sin `filter=` — **tar-slip**: archivo malicioso puede sobrescribir `.bashrc`, `.ssh/authorized_keys` o cualquier archivo del sistema.
- **[HIGH]** Descarga de `skillhub.club` sin verificación de checksum ni firma. Un `skillhub.club` comprometido entrega código arbitrario.
- **[MEDIUM]** Clona repos de terceros sin auditar directamente a `~/.claude/skills/`.

---

## 📋 Stack de Instalación Seguro y Verificado

```bash
# 1. Auditor de seguridad — INSTALAR PRIMERO
/plugin marketplace add trailofbits/skills

# 2. Framework base
git clone https://github.com/affaan-m/everything-claude-code
cd everything-claude-code && bash install.sh python

# 3. Skills verificados
git clone --depth 1 https://github.com/OthmanAdi/planning-with-files
cp -r planning-with-files/skills/planning-with-files ~/.claude/skills/

git clone --depth 1 https://github.com/CosmoBlk/email-marketing-bible
cp email-marketing-bible/SKILL.md ~/.claude/skills/email-marketing-bible.md

git clone --depth 1 https://github.com/blader/humanizer
cp humanizer/SKILL.md ~/.claude/skills/humanizer.md

git clone --depth 1 https://github.com/kostja94/marketing-skills
cp -r marketing-skills/skills ~/.claude/skills/marketing-skills/

git clone --depth 1 https://github.com/Jeffallan/claude-skills
cp -r Jeffallan-claude-skills/skills ~/.claude/skills/jeffallan/

git clone --depth 1 https://github.com/alirezarezvani/claude-skills
cd alirezarezvani-claude-skills && bash scripts/install.sh

git clone --depth 1 https://github.com/sickn33/antigravity-awesome-skills
cd antigravity-awesome-skills && node tools/bin/install.js

# 4. Plugin oficial
/plugin marketplace add anthropics/claude-plugins-official
```

---

## 🔗 Recursos Adicionales

- [Documentación Oficial de Claude Code](https://docs.anthropic.com/claude-code/)
- [Claude Developer Platform](https://console.anthropic.com/)
- [Discord de Claude Code](https://discord.gg/claude-code)

---

## 📝 Licencia

MIT License — Si esta colección te es útil, considera darle ⭐ a los repositorios originales.

---

**Creado con ❤️ por Mario Maldonado (MMI)**
*Auditoría: [trailofbits/skills](https://github.com/trailofbits/skills) + agentes Claude especializados — 22 repos auditados*
