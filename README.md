<div align="center">

# Prince Kumar

**CS @ Texas A&M · Brown Engineering Honors · 4.0 GPA**

Building AI products, developer tooling, and quantitative systems.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-princekumar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/princekumar)
[![GitHub](https://img.shields.io/badge/GitHub-Kumario1-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kumario1)
[![Email](https://img.shields.io/badge/Email-princekmr11%40tamu.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:princekmr11@tamu.edu)
[![npm](https://img.shields.io/badge/npm-@kumario%2Fsynapse-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/@kumario/synapse)

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3500&pause=900&color=58A6FF&center=true&vCenter=true&width=720&lines=Full-stack+%C2%B7+AI+%C2%B7+Mobile+%C2%B7+Quant;Shipping+agent+infra+%26+realtime+systems;Open+to+SWE+%2F+AI+%2F+quant+internships" alt="Typing headline" />

</div>

---

## About

I'm a Computer Science student at **Texas A&M University** (Class of 2029) in the **Craig and Galen Brown Engineering Honors** program. I ship end-to-end systems — from LLM-powered SaaS and coding-agent infrastructure to low-latency market bots and computer-vision pipelines.

Right now I'm focused on **agent coordination**, **AI product engineering**, and **quantitative modeling**.

| | |
| --- | --- |
| **Education** | B.S. Computer Science, Texas A&M · Brown Engineering Honors · **4.0 GPA** |
| **Roles** | Full-Stack Developer @ **Finch / ApplyEasy** · Quantitative Developer @ **Maroon Fund** ($70K+ AUM) |
| **Interests** | Coding agents, realtime systems, ML/CV, prediction markets, mobile |

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [Synapse](https://github.com/Kumario1/synapse)
**Realtime coordination for coding-agent teams**

Published [`@kumario/synapse`](https://www.npmjs.com/package/@kumario/synapse) — a polyglot TypeScript / JS / Python / Go layer that warns agents *before* they edit a symbol a teammate just changed.

- Deterministic contract-conflict engine (not LLM-first)
- WebSocket daemon · MCP tools · Redis fan-out
- tree-sitter sidecars · SQLite / Postgres StateStore

`TypeScript` `WebSockets` `MCP` `Docker`

</td>
<td width="50%" valign="top">

### [agentNotch](https://github.com/Kumario1/agentNotch)
**Claude · Codex · Cursor limits in the Mac notch**

Native Swift macOS app — live usage gauges and sessions for Claude Code, Codex, and Cursor, rendered in the notch. Local-only, no Electron, no cloud.

- Multi-account limit tracking
- Live agent sessions + optional approval hooks
- Launch-at-login · stays out of the Dock

`Swift` `macOS` `Claude` `Codex` `Cursor`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Sentinel-Dev](https://github.com/Kumario1/sentinel-dev)
**Issue → fix → PR agent loop**

Autonomous watcher that polls GitHub issues and dispatches Cursor agents to patch code and open PRs — with humans still in the loop.

- Pluggable engines: in-repo LLM, `@cursor`, Poke VMs
- stdio MCP for approve / decline / instruct
- GitHub Actions label + PR-approval workflows

`TypeScript` `MCP` `GitHub Actions` `AST`

</td>
<td width="50%" valign="top">

### [SkinScan](https://github.com/Kumario1/skinscan)
**Two-stage acne CV pipeline**

YOLOv8m lesion detector → EfficientNetB0 type classifier → rules-based routine mapping. Learning project (not medical software).

- Detector F1 **0.722** on ACNE04
- Classifier test accuracy **91.18%**
- Separates *where* from *what type*

`Python` `YOLOv8` `EfficientNet` `PyTorch`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Finch / ApplyEasy
**AI job-application SaaS**

Five-repo platform: React on Cloudflare, Flask / LangChain backend, Manifest V3 extension, Python CLI — deployed on AWS EC2 with nginx, SSL, and GitHub Actions.

- 100+ jobs/day via n8n + Apify
- Weighted LLM scoring + dual-model generation
- Discord / PostHog activation analytics

`Python` `React` `LangChain` `AWS` `Cloudflare`

</td>
<td width="50%" valign="top">

### Maroon Fund Models
**Quant research for a student fund**

XGBoost buy-the-dip / sell-at-peak classifiers with stationary features, TimeSeriesSplit, and walk-forward validation for a **$70K+ AUM** fund.

- AMZN / NVDA / META pipelines
- Leakage fixes: sell-side ROC AUC **0.64 → 0.97**
- Backtested Sharpe, drawdown, equity curves

`Python` `XGBoost` `pandas` `scikit-learn`

</td>
</tr>
</table>

<details>
<summary><strong>More projects</strong></summary>

<br/>

| Project | Stack | Highlights |
| --- | --- | --- |
| [Southwest Spoilage Model](https://github.com/Kumario1/southwest-spoilage-model) | Python, XGBoost, notebooks | Time-honest 3-class model for airline crew-sequence spoilage — calibrated `P(spoil)` for schedulers |
| High-Freq Arbitrage Bot | C++20, WebSockets | Polymarket / Kalshi bot with lock-free feeds, TLS pooling, and ns latency histograms |
| TAMUSkate | React Native, Supabase | Campus skater social app — maps, heat zones, Google Auth, AI spot safety checks |
| [PiPartner](https://github.com/visshbala21/PiPartner_neighborhood) | iOS, OpenAI, OCR | AI math tutor — **400+ downloads**, 5★, classroom adoption |
| [Xcopilot](https://github.com/Kumario1/xcopilot-tuning) | GCP, Gemini Flash | Fine-tuned personality-aware tweet generation from user history |
| [Akash Chat](https://github.com/Kumario1/akash-chat) | React Native, Vision AI | Multimodal attachments routed through vision models into the LLM |
| [Carbon Footprint Initiative](https://github.com/Kumario1/Carbon-Footprint-Initiative) | Streamlit, ML | Hackathon emissions calculator with visualizations + offset actions |

</details>

---

## Open Source

Contributions merged upstream into high-traffic agent / infra repos:

| Repo | What I shipped |
| --- | --- |
| [headroom](https://github.com/chopratejas/headroom) | Token-savings KPIs for CI gating · normalized Anthropic model IDs across proxy paths |
| [ECC](https://github.com/affaan-m/ECC) | Closed a credential-leak vector (tokens off `curl` argv → stdin) · CI regression guard |
| [CloakBrowser](https://github.com/CloakHQ/CloakBrowser) | Idle Chrome process cleanup · hardened post-scroll click targeting |
| [hermes-agent](https://github.com/NousResearch/hermes-agent) | Windows→WSL cwd translation · session-origin persistence across gateway restarts |

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Frameworks & AI**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)

**Infra & Tools**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=111)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=111)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)

---

## Highlights

- Published **@kumario/synapse** — realtime contract-level coordination for multi-agent coding teams
- Shipped **agentNotch** — native macOS notch UI for Claude / Codex / Cursor usage & sessions
- Built Finch's AI application pipeline processing **100+ jobs/day** with dual-LLM generation and production AWS / Cloudflare infra
- Quant models for a **$70K+ AUM** student fund — leakage fixes lifting sell-side ROC AUC from **0.64 → 0.97**
- Upstream PRs into major agent / infra OSS (headroom, ECC, CloakBrowser, hermes-agent)
- **PiPartner** — 400+ downloads, 5-star rating, classroom adoption

---

## Contact

Open to **software engineering**, **AI / ML**, **mobile**, and **quant** internship opportunities.

<p align="center">
  <a href="mailto:princekmr11@tamu.edu"><img src="https://img.shields.io/badge/Email_me-princekmr11%40tamu.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/princekumar"><img src="https://img.shields.io/badge/Connect_on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  &nbsp;
  <a href="https://github.com/Kumario1"><img src="https://img.shields.io/badge/Follow-@Kumario1-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Kumario1&show_icons=true&theme=transparent&hide_border=true&count_private=true&include_all_commits=true)
![Top langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Kumario1&layout=compact&theme=transparent&hide_border=true&langs_count=8)

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Kumario1&bg_color=00000000&color=58A6FF&line=58A6FF&point=8B949E&area=true&hide_border=true" alt="Activity graph" width="100%" />

</div>
