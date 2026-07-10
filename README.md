<div align="center">

<!-- Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:6b21a8,100:a960ff&height=150&section=header&text=Ruchit%20Das&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%"/>

<!-- Typing -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&pause=1200&color=A960FF&center=true&vCenter=true&width=520&lines=AI+Engineer+%C2%B7+Agentic+Systems;I+don't+prompt+harder+%E2%80%94+I+harness+better;Building+reliable+AI%2C+one+verified+loop+at+a+time" alt="Typing SVG"/>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=flat-square&logo=vercel&logoColor=a960ff)](https://porfolio-eight-green.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=a960ff)](https://www.linkedin.com/in/ruchit-das-3b6a8a252)
[![Dev.to](https://img.shields.io/badge/Dev.to-0d1117?style=flat-square&logo=devdotto&logoColor=a960ff)](https://dev.to/rcids)

</div>

## About

AI engineer focused on **agentic systems** — multi-agent orchestration, local-first RAG, and the infrastructure that makes LLM agents actually reliable. I build across the stack: Python backends, LangGraph pipelines, React/Next.js frontends, and the occasional Rust tool.

- 🔭 Now: neuro-symbolic RAG, multi-agent trading systems, cross-lingual speech ML
- 🌱 Practicing: **Harness Engineering** — treating the agent's environment as the product
- 💬 Ask me about: RAG, LangGraph, MCP servers, multi-agent design

<br/>

## How I build — Harness Engineering

> *"When things fail, don't swap the model — fix the harness."*

A harness is everything outside the model weights. Same model, different harness, fundamentally different results — so I engineer five subsystems around every agent I run:

| Subsystem | What I ship |
|---|---|
| **Instructions** | Short, routing-oriented `AGENTS.md` — a map, not a manual |
| **Environment** | `init.sh`, lockfiles, ≤3-min rebuild from scratch |
| **State** | `progress.md` + git checkpoints — the repo is the spec |
| **Execution** | WIP=1: one feature active, next unlocks only after E2E passes |
| **Feedback** | Executable definition of done — verification decides, not agent confidence |

```
objective (AGENTS.md) → init → run task ⟲ runtime feedback
        → verify: lint → tests → full E2E   (fail → loop back)
        → clean handoff (progress recorded, junk deleted, git green)
```

**Mantras I work by:** done = verification passed, not "code written" · someone in the crew must not believe you · do less but finish · give the agent a methodology, not a task.

<br/>

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [local-clara-agent](https://github.com/Rcidshacker/local-clara-agent)
Neuro-symbolic RAG agent, fully local. Hybrid memory (vector + knowledge graph), HyDE retrieval, self-correcting web fallback.
<br/><sub><code>Python · LangGraph · DSPy · Ollama</code></sub>

</td>
<td width="50%" valign="top">

### 🤖 [Multi-AI-Agent](https://github.com/Rcidshacker/Multi-AI-Agent)
Four agents — research, write, review, publish — that ship finished tech articles to Dev.to autonomously.
<br/><sub><code>Python · LangGraph · Llama 3.1 · Flutter</code></sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🩺 [parkinson-speech-detection](https://github.com/Rcidshacker/parkinson-speech-detection)
Cross-lingual Parkinson's detection from voice. 88-feature eGeMAPS pipeline, 7-model evaluation across Spanish/English/Italian datasets.
<br/><sub><code>Python · scikit-learn · openSMILE</code></sub>

</td>
<td width="50%" valign="top">

### 📈 [autotrade-ai](https://github.com/Rcidshacker/autotrade-ai)
Multi-agent trading platform where 8 investor personas debate every trade before execution.
<br/><sub><code>Next.js · TypeScript · Python</code></sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎵 [Symphony](https://github.com/Rcidshacker/Symphony)
AI-powered terminal music player for developers who never leave the shell.
<br/><sub><code>Rust</code></sub>

</td>
<td width="50%" valign="top">

### 🗂️ [Obsidian-MCP-server](https://github.com/Rcidshacker/Obsidian-MCP-server)
MCP server giving Claude full read/write access to an Obsidian vault — notes as agent memory.
<br/><sub><code>TypeScript · MCP SDK</code></sub>

</td>
</tr>
</table>

<div align="center">
<sub>33 more projects — agents, trading, CV, full-stack — on <a href="https://github.com/Rcidshacker?tab=repositories">the repos tab</a>.</sub>
</div>

<br/>

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,typescript,react,nextjs,fastapi,rust,flutter,pytorch,tensorflow,postgres,docker,git&theme=dark" alt="Tech stack"/>

<sub><code>+ LangGraph · DSPy · Ollama · MCP · Neo4j · pgvector</code></sub>

</div>

<br/>

## Stats

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=Rcidshacker&show_icons=true&hide_border=true&bg_color=00000000&title_color=a960ff&icon_color=a960ff&text_color=8b949e&count_private=true" alt="GitHub stats"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rcidshacker&layout=compact&hide_border=true&bg_color=00000000&title_color=a960ff&text_color=8b949e" alt="Top languages"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Rcidshacker&bg_color=00000000&color=8b949e&line=a960ff&point=ffffff&area=true&hide_border=true" width="92%" alt="Contribution graph"/>

<br/><br/>

<!-- Contribution snake (generated by .github/workflows/snake.yml) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Rcidshacker/Rcidshacker/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Rcidshacker/Rcidshacker/output/github-snake.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/Rcidshacker/Rcidshacker/output/github-snake-dark.svg">
</picture>

</div>

<div align="center">

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a960ff,50:6b21a8,100:0d1117&height=90&section=footer" width="100%"/>

</div>
