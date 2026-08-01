<h1 align="center">Makan Sulaiman</h1>

<p align="center">
  Full-stack developer. I build internal tools, data pipelines and the infrastructure under them.
</p>

<p align="center">
  <a href="https://github.com/schiz0x00?tab=repositories">Repositories</a>
  &nbsp;·&nbsp;
  <a href="mailto:makan.midyaty@gmail.com">makan.midyaty@gmail.com</a>
</p>

---

### About

Mostly TypeScript and Python, with Go for when performance really matters. Web applications,
backend services, automation, and the Linux infrastructure they run on.

Day to day that means Next.js or Astro on the front, Node behind it, PostgreSQL
underneath, and Docker on Linux hosts I run myself — plus Playwright and n8n
where the work is automation rather than product.

Most of my work is in private repositories — what's public is below.

### Selected work

**[instadata](https://github.com/schiz0x00/instadata)** — Async Instagram media scraper, [on PyPI](https://pypi.org/project/instadata/). HTTP-first: a plain anonymous request is the default path, and the expensive tiers (impersonated TLS, authenticated sessions, a headless browser) only wake up when the cheap one stops working. Resumable per page, so an interrupted 8,000-post account restarts where it stopped instead of re-spending the rate-limit budget. Python 3.13, fully typed.

**[image-proxy](https://github.com/schiz0x00/image-proxy)** — Stateless streaming image proxy in Go. Streams the origin response without ever buffering it — no cache, no storage, no processing. SSRF-hardened (private, loopback, link-local and CGNAT ranges blocked, redirect targets checked), per-IP rate limiting, load shedding, host allowlist. Static binaries for linux and darwin on amd64 and arm64.

**[mcp-browser](https://github.com/schiz0x00/mcp-browser)** — MCP server that gives Claude Code a headless browser: navigation, DOM interaction, screenshots, and full request/response traffic capture with aggregated summaries. TypeScript, Playwright over CDP, Streamable HTTP transport with session management, deployed behind Caddy via Docker Compose.

**[kclaude](https://github.com/schiz0x00/kclaude)** — KDE Plasma 6 panel widget that surfaces Claude Code usage limits (5-hour, weekly, monthly) with colour-coded thresholds and reset countdowns. QML + Python, zero runtime dependencies beyond Plasma 6. Unofficial.
