# Awesome MEOK × Council of AI (GSPC)

[![MEOK](https://img.shields.io/badge/MEOK-meok.ai-0ea5e9)](https://meok.ai)
[![GSPC](https://img.shields.io/badge/GSPC-live%20GET%20%2Fapi%2Fgspc-0ea5e9)](https://councilof.ai/api/gspc)
[![Measurement](https://img.shields.io/badge/Measurement-not%20certification-64748b)](https://councilof.ai/api/gspc)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> Curated directory of verified live endpoints, published SDKs/MCP packages, and open repositories across **Council of AI** (`councilof.ai`), **MEOK** (`meok.ai`), and **GSPC** (`GET https://councilof.ai/api/gspc`).

---

## Quick Start

```bash
# Configure Council of AI GSPC MCP (csoai-gspc-mcp + https://councilof.ai/mcp) in your AI client
npx meok-setup --pack gspc

# Quote the live GSPC measurement board verbatim
npx meok-setup --check-gspc

# Run the standalone stdio GSPC board & Ed25519 verifier
npx -y csoai-gspc-mcp

# Install Layer-0 SDKs (TypeScript / Python)
npm i @csoai/layer0
pip install csoai-gspc
```

---

## Verified Live Surfaces

| Surface | URL | Purpose |
| --- | --- | --- |
| **Council of AI** | [`https://councilof.ai`](https://councilof.ai) | Independent AI safety & governance measurement board |
| **GSPC Live JSON Authority** | [`https://councilof.ai/api/gspc`](https://councilof.ai/api/gspc) | Canonical live GSPC board (`totals.public_count` & `totals.lid`, free forever) |
| **GSPC Board UI** | [`https://councilof.ai/board`](https://councilof.ai/board) | Interactive axis & run explorer |
| **GSPC Ed25519 Verifier** | [`https://councilof.ai/gspc-verify`](https://councilof.ai/gspc-verify) | Cryptographic receipt & OpenTimestamps verification (free forever) |
| **GPAI Evidence Map** | [`https://councilof.ai/gpai`](https://councilof.ai/gpai) | EU AI Act GPAI obligation crosswalk (`WIRED` / `PARTIAL` / `UNMEASURED`) |
| **Corrections Ledger** | [`https://councilof.ai/api/corrections`](https://councilof.ai/api/corrections) | Public corrections ledger (free forever) |
| **Single Remote MCP Gateway** | `https://councilof.ai/mcp` | Sole remote Streamable HTTP MCP gateway across Council of AI & MEOK |
| **MEOK Workspace** | [`https://meok.ai`](https://meok.ai) | Human-in-command workspace & shelf (not a second Council) |
| **H.I.M. Charter** | [`https://meok.ai/him/`](https://meok.ai/him/) | Human In Mastery (`MEOK-HIM-001`) human-gated oversight surface |
| **MEOK Hybrid Lab** | [`huggingface.co/spaces/csoai/meok-process-world-v0`](https://huggingface.co/spaces/csoai/meok-process-world-v0) | Public Gradio process-state world lab |
| **GSPC Living Dataset** | [`huggingface.co/datasets/csoai/gspc-board-living`](https://huggingface.co/datasets/csoai/gspc-board-living) | Public mirror of GSPC board snapshots |

---

## Core Open Repositories (`CSOAI-ORG`)

- [`CSOAI-ORG/councilof-ai`](https://github.com/CSOAI-ORG/councilof-ai) — `councilof.ai` web application, `/api/gspc`, `/mcp` gateway, `csoai-gspc-mcp`, and `@csoai/layer0`.
- [`CSOAI-ORG/gspc-board`](https://github.com/CSOAI-ORG/gspc-board) — Scheduled GSPC measurement runner and Hugging Face mirror pipeline.
- [`CSOAI-ORG/gspc-pulse`](https://github.com/CSOAI-ORG/gspc-pulse) — Hourly domain & endpoint pulse watcher (`councilof.ai`, `csoai.org`, `meok.ai`).
- [`CSOAI-ORG/meok-ai-site`](https://github.com/CSOAI-ORG/meok-ai-site) — Production Cloudflare Pages source for `https://meok.ai` and `/him/`.
- [`CSOAI-ORG/meok-ai`](https://github.com/CSOAI-ORG/meok-ai) — MEOK application & Python runtime tree (including deterministic `gspc_board` reader).
- [`CSOAI-ORG/meok-setup`](https://github.com/CSOAI-ORG/meok-setup) — Zero-dependency CLI installer (`npx meok-setup`) for GSPC & MEOK MCP packs.

---

## Honesty Register

**Live authority is `GET https://councilof.ai/api/gspc`** — cite `totals.public_count` and `totals.lid` verbatim from that payload. Do not type static axis counts into documentation.

- **Measurement, not certification.** CSOAI Ltd (UK Companies House `16939677`) measures and signs; it does not certify, accredit, or act as a notified body.
- **MEOK.ai is a shelf / frontend**, not a second Council, and operates no separate remote MCP gateway.
- Prefer honest **UNCHECKABLE** over an unverified claim or fake stamp.

---

## License

MIT © [CSOAI Ltd](https://councilof.ai)
