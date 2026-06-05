# Hi, I'm Ben 👋

I believe in **taking back control** — of our infrastructure, our data, and our relationship with AI.

## 🌍 What I Stand For

**Open source is sovereignty.** Every closed platform is a leash. Every proprietary API is a landlord. I build things locally, own my data, and keep my infrastructure on hardware I can touch.

**Local AI, not corporate AI.** The future of AI isn't a subscription service — it's a 12GB GPU in your bedroom running models you downloaded for free. I run [llama.cpp](https://github.com/ggml-org/llama.cpp) with [TurboQuant+](https://github.com/punkpar/llama-cpp-turboquant) on consumer hardware because the best AI is the one you control.

**Against generative AI for art and culture.** Art is human. Music is human. Creativity isn't a prompt — it's a lived experience. I don't use AI to replace artists, musicians, or creators. That's not progress, that's theft with extra steps.

**AI as a tool, not a master.** The goal isn't to automate humanity out of the loop — it's to give people tools that amplify what they already do well. A homelab dashboard that alerts you before your backups fail. A voice assistant that controls your lights without phoning home to some corporation's cloud. That's AI worth building.

## 🏗️ What I Build

### 🧠 [llama.cpp TurboQuant+](https://github.com/punkpar/llama-cpp-turboquant)
My fork of llama.cpp with TurboQuant+ KV cache quantization — 328 upstream commits merged, running on consumer GPUs (RTX 4070, RTX 3050). Local inference, no API keys, no subscriptions, no telemetry.

### 🏠 [Homelab](https://github.com/punkpar/docker)
Docker-based infrastructure on bare metal. Media stack, AI inference, automation, backups — all self-hosted, all auditable, all mine.

### 📋 [Instructions](https://github.com/punkpar/punkpar)
System prompts and configuration for local LLMs. Because your AI should know *your* context, not some corporation's.

## 💡 My Philosophy

> The best technology is the kind you own. Not rent. Not subscribe to. **Own.**

- 🔒 **Self-hosted first** — if it can't run on my hardware, I don't need it
- 📖 **Open source always** — if I build it, you can build it too
- 🏠 **Local by default** — my data stays on my network
- 🤖 **AI as infrastructure** — not a product, not a service, just a tool
- 🎨 **Human creativity is irreplaceable** — AI should assist, not replace

## 🖥️ Lab

| Host | Role | Hardware |
|------|------|----------|
| **ryzen7600** | AI inference (llama.cpp router) | RTX 4070 12GB, Ryzen 5 7600 |
| **servarr** | Media stack, Docker workhorse | RTX 3050 8GB, i5-7500T |
| **n100** | Always-on backbone, MCP Gateway | Intel N100, 16GB |
| **proxmox** | Virtualization | Proxmox VE |
| **m75q** | Workstation | ThinkCentre M75q |

---

*Built with open source. Running on consumer hardware. Controlled by nobody but me.*
