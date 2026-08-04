<div align="center">

<img src="https://raw.githubusercontent.com/shipiit/.github/main/profile/banner.svg" alt="ShipIt — developer tools that do the work, not just the talking" width="100%">

<br>

**Coding agents · LLM observability · design systems · macOS**

<a href="https://docs.shipiit.com/"><img src="https://img.shields.io/badge/docs-shipiit.com-7C5CFF?style=for-the-badge" alt="Docs"></a>
<a href="https://pypi.org/project/shipit-agent/"><img src="https://img.shields.io/pypi/v/shipit-agent?style=for-the-badge&color=37E5B6&label=shipit-agent" alt="shipit-agent on PyPI"></a>
<a href="https://pypi.org/project/shipit-watcher/"><img src="https://img.shields.io/pypi/v/shipit-watcher?style=for-the-badge&color=37E5B6&label=shipit-watcher" alt="shipit-watcher on PyPI"></a>
<img src="https://komarev.com/ghpvc/?username=shipiit&style=for-the-badge&color=7C5CFF&label=PROFILE+VIEWS" alt="Profile views">

</div>

---

We build the parts of the toolchain that usually get skipped: the agent that
actually opens the pull request, the runtime underneath it, the trace that
explains what an AI system did and what it cost, and the security pass that
runs before the model and costs nothing.

Everything below is open source. Most of it runs on **your** keys and **your**
infrastructure.

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

## 🎨 Design and desktop

| | |
|---|---|
| **[shipit-ui-design](https://github.com/shipiit/shipit-ui-design)** | Senior UI/UX in your terminal — a Claude Code plugin. Eleven skills, nine commands, a nine-category rubric, and a bias toward rich rather than minimal-by-default. Bootstraps design systems, generates polished components, and iterates visually through screenshot critique loops. <br> `TypeScript` `MIT` · [Live →](https://shipit-ui-design.vercel.app) |
| **[ShipIt Palette](https://github.com/shipiit/ShipIt_Palette)** | Pick a color, ship the palette. Fourteen export formats, a live UI playground, and accessibility tools that check contrast where it actually matters. <br> `JavaScript` `MIT` · [Live →](https://shipit-palette.vercel.app) |
| **[Snappilot](https://github.com/shipiit/snappilot)** | The free, open-source Snagit alternative for macOS. Capture, annotate, record and OCR — native Swift, on-device, private. Nothing leaves your machine. <br> `Swift` `SwiftUI` · [Site →](https://snappilot.vercel.app/) |

---

## 📈 Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=shipiit&show_icons=true&theme=react&hide_border=true&bg_color=0B0D17&title_color=7C5CFF&icon_color=37E5B6&text_color=B9C0DC&include_all_commits=true&count_private=true" alt="ShipIt stats" height="165">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shipiit&layout=compact&theme=react&hide_border=true&bg_color=0B0D17&title_color=7C5CFF&text_color=B9C0DC&langs_count=8" alt="Top languages" height="165">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shipiit&theme=react-dark&bg_color=0B0D17&color=B9C0DC&line=7C5CFF&point=37E5B6&hide_border=true&area=true" alt="Contribution activity" width="98%">

</div>

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

<div align="center">

**[Documentation](https://docs.shipiit.com/)** · **[Forge guide](https://shipiit.github.io/forge/)** · **[PyPI](https://pypi.org/user/shipiit/)**

Issues and pull requests are welcome on every repository.

</div>
