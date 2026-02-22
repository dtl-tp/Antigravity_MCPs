# Antigravity MCPs

Este repositorio contiene la configuración, documentación y utilidades relacionadas con los servidores MCP (Model Context Protocol) utilizados en Antigravity.

## Estructura del Repositorio

- `mcp_config.template.json`: Plantilla de configuración para el archivo `mcp_config.json` de Antigravity.
- `docs/`: Documentación detallada sobre el uso y capacidades de cada servidor MCP instalado.

## MCPs Instalados

| MCP Server | Proveedor | Descripción |
|------------|-----------|-------------|
| [NotebookLM](./docs/notebooklm.md) | Google | Interacción con fuentes y libretas de NotebookLM. |
| [Supabase](./docs/supabase.md) | Supabase | Gestión de bases de datos y proyectos de Supabase. |
| [GitHub](./docs/github.md) | Model Context Protocol | Operaciones completas en repositorios de GitHub. |
| [Context7](./docs/context7.md) | Upstash | Inyección de documentación técnica actualizada en tiempo real. |
| [MarkItDown](./docs/markitdown.md) | Microsoft | Conversión de documentos complejos (PDF, Office) a Markdown. |
| [Desktop Commander](./docs/desktop-commander.md) | wonderwhy-er | Control avanzado de terminal, archivos y sistema local. |
| [Next DevTools](./docs/next-devtools.md) | Vercel | Herramientas de diagnóstico e inspección para Next.js 16+. |

## Uso

Para replicar este entorno:
1. Copia el contenido de `mcp_config.template.json` a tu archivo `mcp_config.json` local.
2. Asegúrate de rellenar las variables de entorno y tokens necesarios (ej. `GITHUB_PERSONAL_ACCESS_TOKEN`).
3. Reinicia tu cliente de Antigravity.
