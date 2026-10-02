<h1 align="center">Kizuno</h1>

<p align="center">
  <b>Reverse engineer &amp; full-stack dev — building game internals since 2014.</b>
</p>

<p align="center">
  <a href="https://portfolio.kizuno.net">🌐&nbsp;Portfolio</a> ·
  <a href="mailto:contato@kizuno.net">✉️&nbsp;Email</a> ·
  <a href="https://twitter.com/Kizuno18">𝕏&nbsp;Twitter</a> ·
  <a href="https://youtube.com/@Kizuno18">▶️&nbsp;YouTube</a> ·
  <a href="https://discordapp.com/users/1018287760131498107">💬&nbsp;Discord</a>
</p>

---

### 👋 About

Brazilian engineer working where **low-level reverse engineering** meets **modern full-stack**. I've been shipping software in the Tibia / OTClient / RE space since I was 14 — today that means LuaJIT inline hooks and Windows internals on one side, and Rust workspaces, Go services, Tauri desktops and Next.js dashboards on the other. I like owning products end-to-end: the core, the dashboard, the billing, and the infra underneath.

- 🔭 **Now:** owner & full-stack engineer at **[KizuBot](https://kizubot.com)** · co-founder & backend/dashboard dev at **[CoreGuard](https://coreguard.com.br)** (anti-cheat SaaS) · tech lead on the **PokeAlliance** OTClient.
- 🧰 **Comfort zone:** C/C++ ↔ Rust ↔ Go ↔ TypeScript — from a stripped binary in Ghidra up to a React dashboard on Vercel.
- 🌱 **Lately:** productising RE tooling (reproducible Windows RE labs, inline-hook frameworks) and first-party analytics/infra on Cloudflare Workers.
- 🎧 **Off-keyboard:** music production — the album *Kizuno Feels*.

---

### 🛠️ Tech

**Reverse engineering** — C / C++ · LuaJIT C-API hooking · x86 / x64 inline hooks · Ghidra · IDA Pro · x64dbg · mitmproxy / packet capture · Windows internals · Wine / Bottles · game-protocol analysis

**Systems** — Linux `LD_PRELOAD` · Windows DLLs · Tauri 2 · Docker · KVM / qcow2 · Cloudflare Tunnel

**Backend** — TypeScript · Node.js · Rust · Go · Python · PHP · PostgreSQL · MySQL

**Frontend** — Next.js (App Router) · React · Tauri 2 · Tailwind CSS · shadcn/ui

**Infra & ops** — Vercel · Cloudflare · Docker Compose · Prometheus · Grafana · PM2 · systemd · Stripe · Baileys · BGP / IX.br peering · datacenter colocation

<p>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white">
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
  <img alt="Lua" src="https://img.shields.io/badge/Lua-2C2D72?style=flat&logo=lua&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white">
</p>

---

### 🚀 Selected work

| Project | What it is |
|---|---|
| **[windows-reversing](https://github.com/Kizuno18/windows-reversing)** | Original Ghidra scripts that trace `LuaEngine` internals inside a real game binary, plus a CopyFile-API hook DLL. |
| **tibia-bot-rs** *(private)* | 9-crate Rust workspace — game-protocol parsing, crypto, `mlua` scripting, `bevy_ecs`, `tokio` networking. |
| **bigot-next** *(private)* | From-scratch **Next.js 16 / React 19** rewrite of the Gesior OTServ CMS — 90 App Router pages, 55 API handlers, and a browser-native DAT/SPR/OTB item editor. |
| **kizumetrics** *(private)* | First-party, server-side conversion gateway on **Cloudflare Workers** — a 4-worker monorepo fanning out to 9 vendor APIs, Terraform-managed. |
| **windows-lab** *(private)* | Packer-in-Docker pipeline → one-click Windows RE lab on Hetzner (~3–4 min/VM, 20 in parallel) with Ghidra / IDA and an MCP gateway for remote RE. |
| **mongebot-go** *(private)* | Go concurrency core (pure protocol requests, no browser) with a Tauri 2 desktop shell and a CI/CD pipeline. |
| **[KizuBot](https://kizubot.com)** *(private)* | My flagship automation platform for the Tibia / OTClient ecosystem — bot cores, a Next.js dashboard, licensing & billing, a real-time machine grid, and WhatsApp notifications. |

More on the **[portfolio →](https://portfolio.kizuno.net)**

---

### 🌍 Open source

- **[opentibiabr/otclient](https://github.com/opentibiabr/otclient)** — recurring contributor: forge / vBot fixes, Android build modernisation (vcpkg + LuaJIT), an `ENABLE_ENCRYPTION` crash/corruption fix, and Monk-vocation support across the bot scripts.
- **[WhiskeySockets/Baileys](https://github.com/WhiskeySockets/Baileys)** — finished and shipped the stalled OTP-delay fix for the new pairing-code path ([#643](https://github.com/WhiskeySockets/Baileys/pull/643)); later mirrored into ~17 downstream forks.
- **[opentibiabr/canary](https://github.com/opentibiabr/canary)** — Dockerfile fix for the vcpkg commit-id extraction ([#2797](https://github.com/opentibiabr/canary/pull/2797)).
- **[mehah/otclient](https://github.com/mehah/otclient)** — sponsor of the Bot V8 port (`feat: v8 Bot`); credited in the upstream README.
- **[OmniRoute](https://github.com/diegosouzapw/OmniRoute)** — feature work on an AI model-routing proxy (provider translators, transport options, OAuth routing).

---

### 📊 GitHub

<p align="center">
  <img height="165" alt="Kizuno18's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Kizuno18&show_icons=true&theme=radical&hide_border=true" />
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kizuno18&layout=compact&theme=radical&hide_border=true" />
</p>

<p align="center">
  <img alt="Trophies" src="https://github-profile-trophy.vercel.app/?username=Kizuno18&theme=radical&no-frame=true&no-bg=true&margin-w=4&column=7" />
</p>

---

<p align="center"><i>we are all one — it isn't about me.</i></p>
