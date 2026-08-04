<div align="center">

# ShipIt

**Developer tools that do the work, not just the talking.**

Agents that ship code · observability you can audit · design that looks designed

[![Docs](https://img.shields.io/badge/docs-shipiit.com-7C5CFF?style=flat-square)](https://docs.shipiit.com/)
[![License](https://img.shields.io/badge/license-MIT-37E5B6?style=flat-square)](https://opensource.org/licenses/MIT)

</div>

---

We build the parts of the toolchain that usually get skipped: the agent that
actually opens the pull request, the trace that explains what an AI system did
and what it cost, the security pass that runs before the model and costs
nothing. Everything below is open source, and most of it runs on your own keys
and your own infrastructure.

---

## 🔨 Agents that ship

### [ShipIT Forge](https://github.com/shipiit/forge)

An autonomous coding agent for GitHub. Label an issue and it opens a pull
request. Comment `/review` and it reviews one — with a security lens, inline,
with committable suggestions. It fixes failing CI, writes release notes, and
answers `/help` from your own codebase.

Three deterministic scanners run **before** the model on every pull request —
committed credentials, infrastructure, and the source code itself — with no
model call and no token cost. A check run publishes the verdict, so a finding
can block a merge.

Runs as a hosted GitHub App, a GitHub Action in your own CI, or a CLI. Bring
your own key: Anthropic, OpenAI, Gemini, Vertex AI, Bedrock, Groq, Together,
Ollama, or anything OpenAI-compatible.

`TypeScript` · `MIT` · [**Docs & guide →**](https://shipiit.github.io/forge/)

---

### [shipit_agent](https://github.com/shipiit/shipit_agent)

The Python runtime underneath. Tools, MCP servers, hooks, skills, RAG, memory,
sessions, reasoning and streaming packets — the machinery an agent needs when
it has to survive contact with a real codebase rather than a demo.

`Python` · [**Docs →**](https://docs.shipiit.com/)

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

`Python 3.11+` · `MIT` · zero required dependencies · framework-agnostic

```bash
pip install shipit-watcher
```

---

## 🎨 Design and desktop

### [shipit-ui-design](https://github.com/shipiit/shipit-ui-design)

Senior UI/UX in your terminal — a Claude Code plugin. Eleven skills, nine
commands, a nine-category rubric, and a bias toward rich rather than
minimal-by-default. Bootstraps design systems, generates polished components
and dashboards, and iterates visually through screenshot critique loops.

`TypeScript` · `MIT` · [**Live →**](https://shipit-ui-design.vercel.app)

### [ShipIt Palette](https://github.com/shipiit/ShipIt_Palette)

Pick a color, ship the palette. A colour-palette studio with fourteen export
formats, a live UI playground, and accessibility tools that check contrast
where it actually matters.

`JavaScript` · `MIT` · [**Live →**](https://shipit-palette.vercel.app)

### [Snappilot](https://github.com/shipiit/snappilot)

The free, open-source Snagit alternative for macOS. Capture, annotate, record
and OCR — native Swift, on-device, private. Nothing leaves your machine.

`Swift` · `SwiftUI` · [**Site →**](https://snappilot.vercel.app/)

---

## How we build

**Bring your own key.** Nothing here proxies your traffic through us or marks
up a provider's price. You hold the credentials, you see the bill.

**Deterministic where it can be.** A model is good at judging whether something
is reachable and worth worrying about. It is unreliable at checking four
thousand lines the same way twice. So the checks that can be deterministic are,
they run first, and they cost nothing.

**Not crying wolf is the hard part.** A scanner people stop reading is worse
than no scanner. A trace nobody trusts is worse than no trace. Most of the work
in these tools is in what they *don't* say.

**Own your data.** Traces land in your database. Usage lands in your SQLite
file. Dashboards are token- or account-gated by default, never public.

---

<div align="center">

**[Documentation](https://docs.shipiit.com/)** · **[Forge guide](https://shipiit.github.io/forge/)**

Issues and pull requests are welcome on every repository.

</div>
