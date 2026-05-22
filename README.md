# Hi, I'm Marijan 👋

**Full-stack developer from Osijek. PHP and Linux lover.**

Lead Laravel & DevOps Engineer with 15+ years building production SaaS platforms end-to-end — from architecture and code to servers, CI/CD, observability and day-2 operations. Currently maintaining 20+ production applications across 15+ self-managed Hetzner Linux servers.

Lately I spend most of my time on **AI agents and MCP integrations inside Laravel apps**, an open-source Laravel package for **AI/bot protection** ([mkopcic/laravel-bot-protection on Packagist](https://packagist.org/packages/mkopcic/laravel-bot-protection)), and Go tooling for VPS / home-lab automation.

---

### Pinned projects

**[laravel-bot-protection](https://github.com/mkopcic/laravel-bot-protection)** &nbsp;·&nbsp; *Composer package on [Packagist](https://packagist.org/packages/mkopcic/laravel-bot-protection)*
Drop-in middleware that blocks 33+ AI training crawlers, LLM agents and SEO bots (GPTBot, ClaudeBot, PerplexityBot, Bytespider, AhrefsBot, SemrushBot, Scrapy, curl, …) with a single `composer require`. Adds `X-Robots-Tag` header, `@botProtectionMeta` Blade directive, dynamic `/robots.txt`, `BotBlocked` event, allow-list IPs, dedicated artisan test command and ready-made Nginx / Apache server stubs. 34 Pest tests, CI matrix across **Laravel 10 / 11 / 12 / 13 × PHP 8.1 – 8.4**.

**[ai-agent-demo](https://github.com/mkopcic/ai-agent-demo)** &nbsp;·&nbsp; *Hrčak — personal knowledge agent*
Live app on Laravel Cloud built on the new **Laravel AI SDK**. Users save links, documents and images; the AI analyses, categorises and turns them into a per-user vector store. Chat agent answers questions using the user's private knowledge base + web search, streaming responses through an Inertia / React UI.
Stack: Laravel 13 · Laravel AI SDK · Inertia.js v2 · React 19 · TypeScript · Tailwind 4 · Fortify · Laravel Reverb / Echo · Wayfinder · PostgreSQL · Pest 4 · Vite.

**[vpsctl](https://github.com/mkopcic/vpsctl)** &nbsp;·&nbsp; *Go CLI for managing fleets of VPS servers*
Cobra-based CLI with parallel SSH exec, TCP ping with latency, system updates (apt/yum/apk), systemd service restarts, SQLite-backed job history, and a **REST API + embedded Web UI** (Servers / Execute / History / API tabs — all served from a single Go binary). SSH auth via key, password or interactive prompt. Friendly error translation for the common sudo / unit-not-found cases.

**[react-intertia-laravel](https://github.com/mkopcic/react-intertia-laravel)** &nbsp;·&nbsp; *Codebase running [marijankopcic.from.hr](https://marijankopcic.from.hr)*
Laravel 13 + React 19 + Inertia.js v3 + TypeScript SPA. Fortify 2FA, Wayfinder type-safe routes, shadcn/ui, Tailwind v4. Production SEO/observability stack — schema.org JSON-LD, sitemap, GA4, opcodesio Log Viewer at `/log-viewer`, custom dark-themed error pages.

**[rp-mellon-dev.com](https://github.com/mkopcic/rp-mellon-dev.com)** &nbsp;·&nbsp; *Raspberry Pi 4 (2 GB) homelab*
Docker Compose orchestrating nginx (Alpine), Laravel + PHP 8.4, MariaDB 10.11, Redis 7, phpMyAdmin and Portainer. **Cloudflare Tunnel** for HTTPS without port forwarding — zero-trust alternative to VPN/DDNS. Custom systemd `vscode-cleanup` service that reclaims ~960 MB RAM on boot — resource-conscious engineering on 2 GB hardware.

**[laravel-postgresql-demo](https://github.com/mkopcic/laravel-postgresql-demo)** &nbsp;·&nbsp; *SaaS / admin-panel starter*
Laravel 12 + PostgreSQL + Tabler 1.4 dashboard framework, hand-integrated (no starter-kit lock-in). Spatie suite (permissions, activity log, media library, backup), Laravel Boost MCP server, AI SDK docs, custom Blade component library.

---

### Tech stack

```
Backend     Laravel 12/13 · PHP 8.4 · Livewire · Volt · Flux UI · Alpine.js · Inertia.js
Frontend    React 19 · Vue.js · TypeScript · Tailwind 4 · shadcn/ui · Tabler · Blade
Mobile      Laravel Native (iOS & Android)
Languages   PHP · Go · TypeScript · Bash
DevOps      Linux · Hetzner · Docker · LXC · Proxmox · Nginx · Traefik · Cloudflare Tunnel
Monitoring  Grafana · Prometheus · log aggregation
Databases   MySQL · MariaDB · PostgreSQL · SQLite · Redis
AI          Laravel AI SDK · MCP servers · Laravel Boost · LLM agents · vector stores
Realtime    Laravel Reverb · Echo · WebSockets
Network     MikroTik · WireGuard · iptables · VLAN · Raspberry Pi
Auth/Sec    Laravel Fortify · 2FA · OWASP · bot/AI-crawler protection
Testing     Pest 3 / 4 · PHPUnit · GitHub Actions CI matrices
```

### Where to find me

- 🌐 [marijankopcic.from.hr](https://marijankopcic.from.hr) — personal site
- 💼 [linkedin.com/in/marijan-kopcic](https://www.linkedin.com/in/marijan-kopcic)
- 📦 [packagist.org/packages/mkopcic](https://packagist.org/packages/mkopcic/laravel-bot-protection) — published Composer packages
- 📧 mkopcic@gmail.com
- 🏢 [mellon.hr](https://mellon.hr) — consultancy

---

<sub>Building production systems since 2009. Currently exploring how MCP, the Laravel AI SDK and LLM agents reshape Laravel app architecture.</sub>
