<h1 align="center">Makan Sulaiman</h1>

<p align="center">
  Full-stack developer. I build internal tools, data pipelines and the infrastructure under them.
</p>

<p align="center">
  <a href="https://github.com/schiz0x00?tab=repositories"><img alt="Repositories" src="https://img.shields.io/badge/repositories-view-1f2328?style=flat-square&logo=github&logoColor=white"></a>
  <a href="mailto:makan.midyaty@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-contact-1f2328?style=flat-square&logo=maildotru&logoColor=white"></a>
</p>

---

### About

Mostly TypeScript and Python, with Go where it earns its place. Web applications,
backend services, automation, and the Linux infrastructure they run on.

Most of my work is in private repositories — what's public is below.

### Tech I reach for

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
  <img alt="Astro" src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
</p>
<p>
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
  <img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white">
  <img alt="n8n" src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white">
  <img alt="Qt / QML" src="https://img.shields.io/badge/Qt_%2F_QML-41CD52?style=flat-square&logo=qt&logoColor=white">
</p>

### Selected work

**[instadata](https://github.com/schiz0x00/instadata)** — Async Instagram media scraper, [on PyPI](https://pypi.org/project/instadata/). HTTP-first: a plain anonymous request is the default path, and the expensive tiers (impersonated TLS, authenticated sessions, a headless browser) only wake up when the cheap one stops working. Resumable per page, so an interrupted 8,000-post account restarts where it stopped instead of re-spending the rate-limit budget. Python 3.13, fully typed.

**[image-proxy](https://github.com/schiz0x00/image-proxy)** — Stateless streaming image proxy in Go. Streams the origin response without ever buffering it — no cache, no storage, no processing. SSRF-hardened (private, loopback, link-local and CGNAT ranges blocked, redirect targets checked), per-IP rate limiting, load shedding, host allowlist. Static binaries for linux and darwin on amd64 and arm64.

**[mcp-browser](https://github.com/schiz0x00/mcp-browser)** — MCP server that gives Claude Code a headless browser: navigation, DOM interaction, screenshots, and full request/response traffic capture with aggregated summaries. TypeScript, Playwright over CDP, Streamable HTTP transport with session management, deployed behind Caddy via Docker Compose.

**[kclaude](https://github.com/schiz0x00/kclaude)** — KDE Plasma 6 panel widget that surfaces Claude Code usage limits (5-hour, weekly, monthly) with colour-coded thresholds and reset countdowns. QML + Python, zero runtime dependencies beyond Plasma 6. Unofficial.
