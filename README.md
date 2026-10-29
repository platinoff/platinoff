<p align="center">
  <img src="assets/hero.svg" alt="Platinoff — Mad Developers Inc. — Galaxy Mission Control. rusty is on the orbit." width="100%">
</p>

<p align="center">
  <a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/rust-95%E2%80%93100%25-orange?logo=rust" alt="Rust 95–100%"></a>
  <a href="https://github.com/sponsors/platinoff"><img src="https://img.shields.io/badge/sponsor-GitHub-ea4aaa?logo=github-sponsors" alt="Sponsor"></a>
  <a href="https://github.com/platinoff?tab=repositories"><img src="https://img.shields.io/badge/repos-10-blue?logo=github" alt="10 public repos"></a>
  <a href="https://www.facebook.com/groups/madevinc"><img src="https://img.shields.io/badge/madevinc-community-14f195" alt="Madevinc community"></a>
</p>

# Platinoff — Mad Developers Inc.

> **...actually one guy.** One guy learning Rust with Cursor AI, running an always-on collection of registered products — a decentralized AI power grid for GPU compute and Solana mining, a vision hub, local LLMs, and the tooling that keeps every process alive.

**I build in public.** Everything here is Rust-first (95–100%), versioned as one commit per drip, and supervised by an always-on watchdog at `127.0.0.1:9999`.

---

## 🌀 The galaxy

Every repository is a living node wired to the heart of it — **GSV**:

<p align="center">
  <img src="assets/galaxy.svg" alt="Platinoff ecosystem — GSV hub with rusty, telenetis, and the other public repos" width="100%">
</p>

## 🛠 What I build

| Repo | What it does | Runs at |
|---|---|---|
| [**GSV**](https://github.com/platinoff/GSV) | Galaxy StarWalker Vision — the hub: vision map, ticket board, keep-live watchdog, MCP server | `:9999` |
| [**poolAI**](https://github.com/platinoff/poolAI) | Hybrid decentralized pool grid for AI power + Solana mining | `:8091` |
| [**llama-rs**](https://github.com/platinoff/llama-rs) | Local LLM runner with a live heartbeat | `:8080` |
| [**rusty-engine**](https://github.com/platinoff/rusty-engine) | Pure-Rust MoE inference (GGUF). MIT. Bring your own `GSV_EDGE_TOKEN` | `:8090` |
| [**telenetis**](https://github.com/platinoff/telenetis) | Telegram Mini App shell for the hub. Your bot token stays in `.env` | `:9800` |
| [**sport-forcast**](https://github.com/platinoff/sport-forcast-bin) | Forecast journal. Public download is the binary only | `:9741` |
| [**OmniRoute**](https://github.com/platinoff/OmniRoute) | Free AI gateway — 290 providers, 90+ free tiers, one endpoint | gateway |
| [**LinFS**](https://github.com/platinoff/LinFS) | Linux filesystems on Windows, 100% Rust (no WSL, no Python) | `:9998` |
| [**ORR_DESKTOP**](https://github.com/platinoff/ORR_DESKTOP) | Rust desktop remote control | desktop |
| [**rebook**](https://github.com/platinoff/rebook) | Ebook viewer (KDP publishing toolkit) | desktop |

**Always live** → keep-live probes GSV · telenetis (`:9800`) · llama-rs · rusty-engine in one heartbeat, fail-open. OmniRoute stays a public gateway and is left down on this box by policy. Keys never sit in the repos: each operator mints a bot token and a `GSV_EDGE_TOKEN` for their own hub.

## ⚡ Stack

Rust (`tokio` · `axum`) · WASM 0–5% · HTML/CSS/JS glue · Solana · Cursor AI · MSYS2 bash · MCP / OpenCode / Grok

## 🔭 Currently

- **GSV** hub on `:9999`, with the public plugins wired around it
- **rusty-engine** and **telenetis** are public; secrets stay in each machine's environment
- **sport-forcast** journal ships as a binary on [sport-forcast-bin](https://github.com/platinoff/sport-forcast-bin)

## 💖 Support

All of this is one guy, open-source, Rust-first. If anything here helped you, a star or a coffee means a lot:

🐙 **GitHub Sponsors** — one-off or monthly, zero platform fee  
⭐ **Star a repo** — the galactic way to say thanks  
☀️ **Solana (SOL):** `GcdgNtdE8NEk3z9sQ5jXv2tqguZjSYqPqNAtjsjPNJx8`

- [Sponsor](https://github.com/sponsors/platinoff) · [Facebook group](https://www.facebook.com/groups/madevinc) · [Repositories](https://github.com/platinoff?tab=repositories)