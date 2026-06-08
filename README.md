<!-- ========================= HEADER BANNER ========================= -->
<a href="#">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1021,50:2563eb,100:7c3aed&height=220&section=header&text=Maxwell%20%E2%80%94%20Full%20Stack%20%2B%20AI-Native%20Engineer&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=12%2B%20years%20shipping%20software%20%E2%80%A2%20Claude%20Code%20power%20user%20%E2%80%A2%20Cloud%20%26%20DevOps&descAlignY=58&descSize=18" alt="header"/>
</a>

<!-- ========================= TYPING INTRO ========================= -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=900&color=2563EB&center=true&vCenter=true&width=820&lines=Hi%2C+I'm+Maxwell+%F0%9F%91%8B+Full+Stack+Engineer+from+the+US;Claude+Code+%E2%9C%A6+AI-native+development+workflows;Django+%2B+FastAPI+%2B+React+%E2%80%A2+Python+%2B+JavaScript;DevOps+on+AWS+%26+Azure+%E2%80%A2+Docker+%E2%80%A2+Kubernetes+%E2%80%A2+Terraform;Turning+prompts+into+production+systems+for+12%2B+years)](https://git.io/typing-svg)

<!-- profile views + followers + a fun badge row -->
<img src="https://komarev.com/ghpvc/?username=maxwellfet928&label=Profile%20Views&color=2563eb&style=for-the-badge" alt="views" />
<a href="https://github.com/maxwellfet928?tab=followers">
  <img src="https://img.shields.io/github/followers/maxwellfet928?label=Followers&style=for-the-badge&color=7c3aed" alt="followers" />
</a>
<img src="https://img.shields.io/badge/Experience-12%2B%20years-success?style=for-the-badge&color=16a34a" alt="experience" />
<img src="https://img.shields.io/badge/Open%20to-Collab%20%26%20Consulting-orange?style=for-the-badge" alt="open" />

</div>

---

## 🧠 About Me — One Engineer Orchestrating a Fleet

> Senior Full-Stack & AI-Native Engineer in the **United States 🇺🇸** with **12+ years** in production software.
> I direct **Claude Code sub-agents** like a tech lead directs a team — fanning them out across the entire stack while I own the architecture.

```mermaid
flowchart TD
    M["👨‍💻 Maxwell<br/>12+ yrs · Architect & Reviewer"] --> CC{{"✦ Claude Code<br/>Orchestrator"}}

    CC --> A1["🤖 Backend Agent"]
    CC --> A2["🤖 Frontend Agent"]
    CC --> A3["🤖 DevOps Agent"]
    CC --> A4["🤖 Test & Review Agent"]

    A1 --> B["🐍 Django · FastAPI<br/>Python · PostgreSQL · Redis"]
    A2 --> F["⚛️ React · Next.js<br/>TypeScript · Tailwind"]
    A3 --> D["☁️ AWS · Azure<br/>Docker · K8s · Terraform"]
    A4 --> T["✅ pytest · Playwright<br/>CI gates · code review"]

    B --> SHIP["🚀 Production"]
    F --> SHIP
    D --> SHIP
    T --> SHIP

    style M fill:#0b1021,color:#fff,stroke:#2563eb,stroke-width:2px
    style CC fill:#D97757,color:#fff,stroke:#fff
    style A1 fill:#7c3aed,color:#fff
    style A2 fill:#7c3aed,color:#fff
    style A3 fill:#7c3aed,color:#fff
    style A4 fill:#7c3aed,color:#fff
    style SHIP fill:#16a34a,color:#fff,stroke:#fff,stroke-width:2px
```

<div align="center">
<i>Sub-agents do the parallel toil across the stack — I stay focused on design, trade-offs, and the diff.</i>
</div>

---

## ✦ 1. Claude Code — My AI-Native Development Engine

> *"The hottest new programming language is English."* — **Andrej Karpathy**, who popularized **vibe coding**.
> Claude Code, created by **Boris Cherny** at Anthropic, is the agentic terminal that turns that idea into shipped software — and it's where I spend most of my engineering day.

<div align="center">
<img src="https://img.shields.io/badge/Claude%20Code-Daily%20Driver-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/Agentic-Workflows-7c3aed?style=for-the-badge" />
<img src="https://img.shields.io/badge/MCP-Connected-2563eb?style=for-the-badge" />
</div>

I treat Claude Code as a **fleet of engineers in my terminal**, not an autocomplete. My workflow is heavily inspired by **Andrej Karpathy's** agent-first mindset and **Boris Cherny's** "let the agent run, then review the diff" philosophy.

### 🔧 The Claude Code features I lean on every day

| Feature | How I use it to build powerful processes |
| :-- | :-- |
| 🤖 **Sub-agents (parallel fleets)** | Spin up multiple agents to explore, plan, and implement different parts of a feature *in parallel* — then merge the diffs. |
| 🧩 **MCP servers** | Wire Claude into Postgres, GitHub, Sentry, AWS, and internal APIs so the agent acts on **live context**, not guesses. |
| 🪝 **Hooks** | Auto-run linters, tests, and formatters on every edit — the agent self-corrects before I ever see the code. |
| ⚡ **Custom slash commands** | Reusable `/deploy`, `/code-review`, `/security-review` workflows encoded once, run forever. |
| 🧠 **CLAUDE.md memory** | Project conventions, architecture, and guardrails live in repo so every session starts *fully briefed*. |
| 📋 **Plan Mode** | Read-only architecture passes before a single line changes — no surprises in the diff. |
| 🛠️ **Skills** | Packaged, repeatable capabilities (API scaffolds, migrations, IaC) the agent invokes on demand. |
| 🚀 **Headless mode (`claude -p`)** | Drop Claude Code straight into **CI/CD** for automated reviews, refactors, and changelogs. |

### 🔁 My real-world Claude Code loop

```mermaid
flowchart LR
    A[🗣️ Describe intent<br/>in plain English] --> B[📋 Plan Mode<br/>architecture pass]
    B --> C[🤖 Parallel sub-agents<br/>explore + implement]
    C --> D[🪝 Hooks run<br/>lint · test · format]
    D --> E{✅ Green?}
    E -- no --> C
    E -- yes --> F[👀 Review the diff]
    F --> G[🚀 Headless CI<br/>ship to AWS / Azure]
    style A fill:#2563eb,color:#fff
    style C fill:#7c3aed,color:#fff
    style G fill:#16a34a,color:#fff
```

**Result:** features that used to take days now ship in hours — with tests, reviews, and infra changes handled by agents while I stay focused on architecture and product.

---

## ✦ 2. Full-Stack Engineering

> Django + FastAPI on the back, React + TypeScript on the front, glued with clean APIs and real tests.

<div align="center">

### Languages & Core
<img src="https://skillicons.dev/icons?i=python,js,ts,html,css,go,bash&theme=dark" />

### Backend
<img src="https://skillicons.dev/icons?i=django,fastapi,flask,nodejs,express,graphql,postgres,redis,mysql,mongodb&theme=dark" />

### Frontend
<img src="https://skillicons.dev/icons?i=react,nextjs,vue,tailwind,redux,vite,sass,figma&theme=dark" />

</div>

<details>
<summary><b>🧪 What I actually build (click to expand)</b></summary>

<br/>

- **APIs:** Django REST Framework & FastAPI services with async I/O, Pydantic validation, OpenAPI docs, and JWT/OAuth2 auth.
- **Frontends:** React + Next.js apps with TypeScript, server components, and design-system-driven UIs.
- **Data:** PostgreSQL + Redis, migrations, query tuning, Celery/async task queues.
- **Quality:** pytest, Playwright, type checking, and CI gates — agents keep coverage honest.

</details>

---

## ✦ 3. DevOps · AWS · Azure

> Infrastructure as code, containers everywhere, and pipelines that deploy themselves.

<div align="center">

### Cloud & Platforms
<img src="https://skillicons.dev/icons?i=aws,azure,gcp,cloudflare&theme=dark" />

### Containers, IaC & CI/CD
<img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,ansible,githubactions,jenkins,nginx,grafana,prometheus&theme=dark" />

</div>

| Area | Toolbelt |
| :-- | :-- |
| **AWS** | ECS / EKS · Lambda · S3 · RDS · CloudFront · IAM · CloudWatch |
| **Azure** | AKS · App Service · Functions · Blob Storage · Azure DevOps · Entra ID |
| **IaC & Automation** | Terraform · Ansible · Helm · GitHub Actions · Docker Compose |
| **Observability** | Prometheus · Grafana · CloudWatch · Sentry |

---

## 📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=maxwellfet928&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0b1021&title_color=2563eb&icon_color=7c3aed" alt="stats" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=maxwellfet928&layout=compact&theme=tokyonight&hide_border=true&bg_color=0b1021&title_color=2563eb&langs_count=8" alt="top langs" />

<br/>

<img src="https://streak-stats.demolab.com?user=maxwellfet928&theme=tokyonight&hide_border=true&background=0b1021&ring=2563eb&fire=7c3aed&currStreakLabel=2563eb" alt="streak" />

<br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=maxwellfet928&theme=tokyo-night&bg_color=0b1021&color=2563eb&line=7c3aed&point=ffffff&hide_border=true&area=true" alt="activity graph" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=maxwellfet928&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=4" alt="trophies" />

</div>

---

## 💬 A meme to close on

<div align="center">

> *"It works on my machine."*  —  so I shipped the machine. 🐳

<img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="260" alt="deploy meme"/>

</div>

---


<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:2563eb,100:0b1021&height=120&section=footer" alt="footer"/>
