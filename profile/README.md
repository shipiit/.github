<div align="center">

<a href="https://shipiit.com/"><img src="https://raw.githubusercontent.com/shipiit/.github/main/profile/banner.jpg" alt="ShipIt — AI agents, developer tools and native Mac apps. Flagship: Vouchline, research agents that verify what they find. Also Forge, shipit-agent, Watchtower, MacSweep, Snappilot, KeyVault, UI Design and Palette." width="100%"></a>

<br>

**Coding agents · research agents · LLM observability · native Mac apps · design systems · security**

<a href="https://shipiit.com/"><img src="https://img.shields.io/badge/web-shipiit.com-7C5CFF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="shipiit.com"></a>
<a href="https://iamrraj.com/"><img src="https://img.shields.io/badge/founder-iamrraj.com-37E5B6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="iamrraj.com"></a>
<a href="https://www.linkedin.com/in/iamrraj/"><img src="https://img.shields.io/badge/LinkedIn-Rahul%20Raj-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Rahul Raj on LinkedIn"></a>
<a href="https://docs.shipiit.com/"><img src="https://img.shields.io/badge/docs-docs.shipiit.com-1F2544?style=for-the-badge" alt="Docs"></a>
<a href="https://pypi.org/project/shipit-agent/"><img src="https://img.shields.io/pypi/v/shipit-agent?style=for-the-badge&color=37E5B6&label=shipit-agent" alt="shipit-agent on PyPI"></a>
<a href="https://pypi.org/project/shipit-watcher/"><img src="https://img.shields.io/pypi/v/shipit-watcher?style=for-the-badge&color=37E5B6&label=shipit-watcher" alt="shipit-watcher on PyPI"></a>
<img src="https://komarev.com/ghpvc/?username=shipiit&style=for-the-badge&color=7C5CFF&label=PROFILE+VIEWS" alt="Profile views">

</div>

---

We build the parts of the toolchain that usually get skipped: the agent that
actually opens the pull request, the runtime underneath it, the trace that
explains what an AI system did and what it cost, and the security pass that
runs before the model and costs nothing.

Alongside them, we make small native apps for the computer you work on: a Mac
cleaner that explains every file before it touches it, a screen-capture studio,
and a password manager with no server behind it.

Everything below is open source. Most of it runs on **your** keys, **your**
infrastructure and **your** Mac.

## 🧭 Every ShipIt product

| | Product | What it is | Platform | Status | Links |
|---|---|---|---|---|---|
| 🔨 | **[Forge](https://github.com/shipiit/forge)** | Autonomous GitHub coding agent: fixes issues, opens PRs, reviews code with a security lens, auto-fixes CI | GitHub App · Action · CLI | ![](https://img.shields.io/github/v/release/shipiit/forge?style=flat-square&label=&color=7C5CFF&sort=semver) | [Guide](https://shipiit.github.io/forge/) |
| 🤖 | **[shipit-agent](https://github.com/shipiit/shipit_agent)** | Python runtime for tool-using agents: MCP, RAG, memory, permissions, streaming, any LLM | Python 3.11+ | ![](https://img.shields.io/pypi/v/shipit-agent?style=flat-square&label=&color=7C5CFF) | [Docs](https://docs.shipiit.com/) · [PyPI](https://pypi.org/project/shipit-agent/) |
| 📊 | **[Watchtower](https://github.com/shipiit/shipit-watchtower)** | Observability for LLM apps: tracing, prompt governance, cost allocation, PII masking | Python 3.11+ | ![](https://img.shields.io/pypi/v/shipit-watcher?style=flat-square&label=&color=7C5CFF) | [PyPI](https://pypi.org/project/shipit-watcher/) |
| 🧹 | **[MacSweep](https://github.com/shipiit/mac-sweep)** | Clean, protect, speed up and understand your Mac; AI usage tracking built in | macOS 15+ | ![](https://img.shields.io/github/v/release/shipiit/mac-sweep?style=flat-square&label=&color=7C5CFF&sort=semver) | [Website](https://shipiit.github.io/mac-sweep-website/) · [Download](https://github.com/shipiit/mac-sweep/releases/latest) |
| 📸 | **[Snappilot](https://github.com/shipiit/snappilot)** | Screen capture studio: capture, annotate, record, OCR — on-device | macOS 14+ | ![](https://img.shields.io/github/v/release/shipiit/snappilot?style=flat-square&label=&color=7C5CFF&sort=semver) | [Website](https://snappilot.vercel.app/) · [Download](https://github.com/shipiit/snappilot/releases/latest/download/Snappilot.dmg) |
| 🔐 | **[KeyVault](https://github.com/shipiit/keyvault)** | Zero-knowledge password manager with TOTP — no server, no account | Chrome · Chromium | ![](https://img.shields.io/github/v/release/shipiit/keyvault?style=flat-square&label=&color=7C5CFF&sort=semver) | [Website](https://shipiit.github.io/keyvault/) |
| 🎨 | **[shipit-ui-design](https://github.com/shipiit/shipit-ui-design)** | Senior UI/UX in your terminal — Claude Code plugin with 11 skills and 9 commands | Claude Code | open source | [Live demo](https://shipit-ui-design.vercel.app) |
| 🌈 | **[ShipIt Palette](https://github.com/shipiit/ShipIt_Palette)** | One hex to a full design system: scales, previews, 14 export formats, Figma | Web | open source | [Live](https://shipit-palette.vercel.app) |
| ✅ | **Vouchline** | Research agents where every claim links to its quoted source, re-checked | Web · API | in development | — |
| 🔁 | **Relay** | Self-hosted platform where Claude Code takes an issue to a verified pull request | Self-hosted | in development | — |
| 🔍 | **Pentest skills** | One `/pentest` command: full, evidence-based security audit with an HTML report | Claude Code | private beta | — |
| 🛡️ | **Sentinel** | Autonomous AI penetration testing with 23 attacker agents | SaaS | closed beta | — |
| 🧪 | **ShipitQA** | Evidence-first autonomous product testing in real browsers | Web | in development | — |
| ☁️ | **ShipIt Cloud** | Run ShipIt agents remotely with the same permissions, costs and traces | Cloud | in development | — |
| ⌨️ | **ShipIt CLI** | Terminal agent with 65+ tools and Slack / Discord / Telegram / WhatsApp bots | macOS · Linux | preparing OSS release | — |

---

## 🗺️ How it fits together

One runtime, many surfaces. The same agent core powers the GitHub teammate,
the terminal, and the cloud — with observability wired through everything.

```mermaid
flowchart LR
    subgraph surfaces["Surfaces"]
        forge["🔨 Forge<br/>GitHub App · Action · CLI"]
        cli["⌨️ ShipIt CLI<br/>terminal agent"]
        cloud["☁️ ShipIt Cloud<br/>remote control plane"]
    end

    subgraph core["Core"]
        runtime["🤖 shipit-agent<br/>Python agent runtime<br/>tools · MCP · RAG · memory · permissions"]
    end

    subgraph quality["Quality & Security"]
        qa["🧪 ShipitQA<br/>autonomous browser testing"]
        sec["🛡️ Sentinel<br/>autonomous AI pentesting"]
    end

    obs["📊 Watchtower<br/>tracing · cost · PII masking"]

    forge --> runtime
    cli --> runtime
    cloud --> runtime
    runtime --> qa
    runtime --> sec
    runtime -.traces.-> obs
    forge -.traces.-> obs
    qa -.evidence.-> obs
```

---

## 🔨 Agents that ship

<table>
<tr><td width="50%" valign="top">

### [ShipIT Forge](https://github.com/shipiit/forge)

**An autonomous coding agent for GitHub.**

Label an issue and it opens a pull request. Comment `/review` and it reviews
one — with a security lens, inline, with committable suggestions. It fixes
failing CI, writes release notes, and answers `/help` from your own codebase.

Three deterministic scanners run **before** the model on every pull request —
committed credentials, infrastructure, and the source code itself — with no
model call and no token cost. A check run publishes the verdict, so a finding
can block a merge.

Hosted GitHub App, GitHub Action, or CLI. Nine providers.

`TypeScript` `MIT` · [**Guide →**](https://shipiit.github.io/forge/)

</td><td width="50%" valign="top">

### [SHIPIT Agent](https://github.com/shipiit/shipit_agent)

**The Python runtime underneath.**

A small, explicit runtime for production agents. You bring an LLM; it gives you
the loop around it — tool calling, retries, streaming, memory, sessions, a
rule-based permission layer, prompt caching, and cost tracking.

Then the batteries: 40+ built-in tools, 17 SaaS connectors, MCP servers, RAG,
skills, hooks, deep multi-agent orchestration and browser automation.

Provider-agnostic by design — the same agent code runs on OpenAI, Anthropic,
Bedrock, Vertex, Gemini, Groq, Together, Ollama, or 100+ models through
LiteLLM. Swap the model in one line; nothing else changes.

`Python 3.11+` `MIT` · [**Docs →**](https://docs.shipiit.com/)

```bash
pip install shipit-agent
```

</td></tr>
</table>

---

## 🖥️ Native apps for your Mac

<table>
<tr><td width="50%" valign="top">

### [MacSweep](https://github.com/shipiit/mac-sweep)

**Clean, protect, speed up and understand your Mac — in one native app.**

Smart Scan checks junk, security, speed and apps in about 20 seconds. Every
cleanup item says what it is and what happens if you delete it, and everything
goes to the Trash first. Malware and download protection, a security score,
Memory Guard for low-RAM moments, Startup Guard for new launch agents, a
developer hub (Docker, Homebrew, Xcode, `node_modules`, Git repos, ports), and
Claude Code / Codex usage with cost by model and live plan limits.

`Swift` `SwiftUI` · macOS 15+ · 600+ tests · no dependencies · no analytics
<br>[**Download →**](https://github.com/shipiit/mac-sweep/releases/latest) · [Website →](https://shipiit.github.io/mac-sweep-website/)

</td><td width="50%" valign="top">

### [Snappilot](https://github.com/shipiit/snappilot)

**The free, open-source screen-capture studio for macOS.**

Region, window, full-screen and scrolling capture with a magnifier loupe;
annotate with arrows, text, highlights and live pixelate/blur redaction; record
the screen with audio; pull text out of any image with on-device OCR. Every
capture lands in a local library you can search by the text inside it.

No telemetry, no cloud, no sign-in — ScreenCaptureKit and Apple's on-device
frameworks, no Electron.

`Swift` `SwiftUI` `MIT` · macOS 14+
<br>[**Download →**](https://github.com/shipiit/snappilot/releases/latest/download/Snappilot.dmg) · [Website →](https://snappilot.vercel.app/)

</td></tr>
</table>

---

## 📊 Know what your AI actually did

### [shipit-watchtower](https://github.com/shipiit/shipit-watchtower)

Observability for LLM applications. One coherent record of what an AI system
did: which prompt ran, what it cost, which tenant it belonged to, which tools
it called, what it retrieved — and why it chose what it chose.

PII is masked **before** anything is persisted or leaves the process, because
masking at display time is theatre once the raw value is on somebody else's
infrastructure. Events fan out to Langfuse for analysis and to your own
database as the system of record, with failures isolated per destination.

`Python 3.11+` `MIT` · zero required dependencies · framework-agnostic

```bash
pip install shipit-watcher
```

---

## 🔐 Design and security

| | |
|---|---|
| **[KeyVault](https://github.com/shipiit/keyvault)** | A password manager with **no server to trust**. Local-only and zero-knowledge for Chromium browsers: AES-GCM-256 vault under a PBKDF2-derived key, RFC 6238 TOTP with QR scanning, autofill that works on React/Vue apps, a bias-free CSPRNG generator, Watchtower for weak/reused/breached passwords, and importers for 1Password, Bitwarden, LastPass and Chrome. No backend, no account, no telemetry — breach checking is optional, off by default, and never sends the password. <br> `JavaScript` `MIT` · 936 tests · 97% coverage · two runtime deps (preact + jsQR) · [Site →](https://shipiit.github.io/keyvault/) |
| **[shipit-ui-design](https://github.com/shipiit/shipit-ui-design)** | Senior UI/UX in your terminal — a Claude Code plugin. Eleven skills, nine commands, a nine-category rubric, and a bias toward rich rather than minimal-by-default. Bootstraps design systems, generates polished components, and iterates visually through screenshot critique loops. <br> `TypeScript` `MIT` · [Live →](https://shipit-ui-design.vercel.app) |
| **[ShipIt Palette](https://github.com/shipiit/ShipIt_Palette)** | Pick a color, ship the palette. One hex becomes a full design system: shade scales, live UI previews and an HTML playground, 18+ tools, 14 export formats in HEX/RGBA/HSL/OKLCH, a Figma integration, and accessibility tools that check contrast where it actually matters. Pairs with shipit-ui-design. <br> `JavaScript` `MIT` · [Live →](https://shipit-palette.vercel.app) |

---

## 📈 The projects at a glance

<div align="center">

| Project | Version | Stars | Language | Last commit |
|---|---|---|---|---|
| [forge](https://github.com/shipiit/forge) | ![](https://img.shields.io/github/v/release/shipiit/forge?style=flat-square&label=&color=7C5CFF&sort=semver) | ![](https://img.shields.io/github/stars/shipiit/forge?style=flat-square&label=&color=37E5B6) | ![](https://img.shields.io/github/languages/top/shipiit/forge?style=flat-square&color=0B0D17) | ![](https://img.shields.io/github/last-commit/shipiit/forge?style=flat-square&label=&color=1F2544) |
| [shipit_agent](https://github.com/shipiit/shipit_agent) | ![](https://img.shields.io/pypi/v/shipit-agent?style=flat-square&label=&color=7C5CFF) | ![](https://img.shields.io/github/stars/shipiit/shipit_agent?style=flat-square&label=&color=37E5B6) | ![](https://img.shields.io/github/languages/top/shipiit/shipit_agent?style=flat-square&color=0B0D17) | ![](https://img.shields.io/github/last-commit/shipiit/shipit_agent?style=flat-square&label=&color=1F2544) |
| [shipit-watchtower](https://github.com/shipiit/shipit-watchtower) | ![](https://img.shields.io/pypi/v/shipit-watcher?style=flat-square&label=&color=7C5CFF) | ![](https://img.shields.io/github/stars/shipiit/shipit-watchtower?style=flat-square&label=&color=37E5B6) | ![](https://img.shields.io/github/languages/top/shipiit/shipit-watchtower?style=flat-square&color=0B0D17) | ![](https://img.shields.io/github/last-commit/shipiit/shipit-watchtower?style=flat-square&label=&color=1F2544) |
| [shipit-ui-design](https://github.com/shipiit/shipit-ui-design) | — | ![](https://img.shields.io/github/stars/shipiit/shipit-ui-design?style=flat-square&label=&color=37E5B6) | ![](https://img.shields.io/github/languages/top/shipiit/shipit-ui-design?style=flat-square&color=0B0D17) | ![](https://img.shields.io/github/last-commit/shipiit/shipit-ui-design?style=flat-square&label=&color=1F2544) |
| [ShipIt_Palette](https://github.com/shipiit/ShipIt_Palette) | — | ![](https://img.shields.io/github/stars/shipiit/ShipIt_Palette?style=flat-square&label=&color=37E5B6) | ![](https://img.shields.io/github/languages/top/shipiit/ShipIt_Palette?style=flat-square&color=0B0D17) | ![](https://img.shields.io/github/last-commit/shipiit/ShipIt_Palette?style=flat-square&label=&color=1F2544) |
| [snappilot](https://github.com/shipiit/snappilot) | ![](https://img.shields.io/github/v/release/shipiit/snappilot?style=flat-square&label=&color=7C5CFF&sort=semver) | ![](https://img.shields.io/github/stars/shipiit/snappilot?style=flat-square&label=&color=37E5B6) | ![](https://img.shields.io/github/languages/top/shipiit/snappilot?style=flat-square&color=0B0D17) | ![](https://img.shields.io/github/last-commit/shipiit/snappilot?style=flat-square&label=&color=1F2544) |
| [mac-sweep](https://github.com/shipiit/mac-sweep) | ![](https://img.shields.io/github/v/release/shipiit/mac-sweep?style=flat-square&label=&color=7C5CFF&sort=semver) | ![](https://img.shields.io/github/stars/shipiit/mac-sweep?style=flat-square&label=&color=37E5B6) | ![](https://img.shields.io/github/languages/top/shipiit/mac-sweep?style=flat-square&color=0B0D17) | ![](https://img.shields.io/github/last-commit/shipiit/mac-sweep?style=flat-square&label=&color=1F2544) |
| [keyvault](https://github.com/shipiit/keyvault) | ![](https://img.shields.io/github/v/release/shipiit/keyvault?style=flat-square&label=&color=7C5CFF&sort=semver) | ![](https://img.shields.io/github/stars/shipiit/keyvault?style=flat-square&label=&color=37E5B6) | ![](https://img.shields.io/github/languages/top/shipiit/keyvault?style=flat-square&color=0B0D17) | ![](https://img.shields.io/github/last-commit/shipiit/keyvault?style=flat-square&label=&color=1F2544) |

</div>

---

## 🧪 In the lab — coming next

The public repos are the foundation. On top of them, currently in private
development and closed beta:

| | | |
|---|---|---|
| ✅ **Vouchline** | Research agents that verify what they find. Every claim in a report links to the source it came from, with the quoted passage — and the system re-checks each quote itself before you see it. | *in development* |
| 🔁 **Relay** | A self-hosted platform where the Claude Code CLI is the engineer: it takes an issue to a reviewed pull request, has three independent agents try to refute its own fix, and opens the PR only if they cannot. Every tool call is recorded. | *in development* |
| 🔍 **Pentest skills** | One `/pentest` command for Claude Code: scope form, recon, static review across every stack, scanners, local exploit verification, read-only dynamic tests and an HTML report — the scripts count, the model judges. | *private beta* |
| 🛡️ **Sentinel** | Autonomous AI penetration testing — **23 autonomous ReAct attacker agents** that find, validate and explain real vulnerabilities in web apps and APIs: code-level root cause, OWASP mapping, live exploit proof, auditor-ready reports. Multi-tenant SaaS. | *closed beta* |
| 🧪 **ShipitQA** | Evidence-first autonomous product testing — a QA control plane driving real Playwright browsers, with human takeover for OTP/login boundaries and reproducible engineering reports where every issue carries exact evidence. | *in development* |
| ☁️ **ShipIt Cloud** | The cloud control plane — run ShipIt agents remotely on your repos with the same permission layer, cost tracking, and traces you get locally. | *in development* |
| ⌨️ **ShipIt CLI** | The full terminal agent — 65+ tools, 10+ providers, computer use, browser automation, deep research, and two-way Slack / Discord / Telegram / WhatsApp bots. | *preparing OSS release* |

---

## How we build

**Bring your own key.** Nothing here proxies your traffic through us or marks
up a provider's price. You hold the credentials, you see the bill.

**Deterministic where it can be.** A model is good at judging whether something
is reachable and worth worrying about. It is unreliable at checking four
thousand lines the same way twice. So the checks that *can* be deterministic
are, they run first, and they cost nothing.

**Not crying wolf is the hard part.** A scanner people stop reading is worse
than no scanner. A trace nobody trusts is worse than no trace. Most of the work
in these tools is in what they *don't* say.

**Own your data.** Traces land in your database. Usage lands in your SQLite
file. Dashboards are account- or token-gated by default, never public.

---

## 👤 Who's behind ShipIt

ShipIt is built by **[Rahul Raj](https://iamrraj.com/)** — a full-stack &
AI engineer in Warsaw, Poland, who has shipped production systems across
edtech, automotive, insurance, and health, and now spends his time on one
question: **how far can autonomous agents go before a human needs to step in —
and how do you make that boundary safe, observable, and cheap?**

Every tool here comes from running agents in production and hitting the same
walls: agents that talk instead of committing, traces nobody can read, security
scans nobody trusts, and bills nobody can attribute. ShipIt is the toolchain
that came out of fixing those.

<a href="https://github.com/iamrraj"><img src="https://img.shields.io/badge/GitHub-iamrraj-24292e?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://iamrraj.com"><img src="https://img.shields.io/badge/Website-iamrraj.com-7C5CFF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
<a href="https://www.linkedin.com/in/iamrraj/"><img src="https://img.shields.io/badge/LinkedIn-Rahul%20Raj-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:rahul@iamrraj.com"><img src="https://img.shields.io/badge/Email-rahul@iamrraj.com-37E5B6?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>

---

<div align="center">

**[shipiit.com](https://shipiit.com/)** · **[iamrraj.com](https://iamrraj.com/)** · **[LinkedIn](https://www.linkedin.com/in/iamrraj/)** · **[Documentation](https://docs.shipiit.com/)** · **[Forge guide](https://shipiit.github.io/forge/)** · **[MacSweep](https://shipiit.github.io/mac-sweep-website/)** · **[Snappilot](https://snappilot.vercel.app/)** · **[KeyVault](https://shipiit.github.io/keyvault/)** · **[PyPI](https://pypi.org/user/shipiit/)**

Issues and pull requests are welcome on every repository.

</div>
