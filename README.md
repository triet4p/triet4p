<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,100:2563eb&height=180&section=header&text=Hi%20there,%20I'm%20Triet%20👋&fontSize=38&fontColor=ffffff&fontAlignY=38" width="100%" alt="Header Banner" />
</p>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=2800&pause=1000&color=38BDF8&center=true&vCenter=true&width=620&height=40&lines=AI+Engineer+%C2%B7+Physical+AI+%26+Robotics;Autonomous+Multi-Agent+Systems+%26+Memory;High-Throughput+Lakehouse+%26+Knowledge+Graphs;Frontier+AI+Under+Real-World+Physical+Constraints" alt="Typing Subtitle" />
  </a>
</p>

<p align="center">
  <a href="https://trietlm0306portfolio.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-trietlm0306-blue?style=flat-square&logo=vercel" alt="Portfolio"/>
  </a>
  <a href="mailto:trietlm0306@gmail.com">
    <img src="https://img.shields.io/badge/Email-trietlm0306%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/triet4p">
    <img src="https://img.shields.io/badge/GitHub-triet4p-181717?style=flat-square&logo=github" alt="GitHub"/>
  </a>
</p>

---

### 🧠 About Me

- 🔭 **Physical AI & Robotics:** Training Vision-Language-Action (VLA) models and Imitation Learning policies (ACT, Diffusion Policy) on physical hardware (**SO-ARM-101**) with synchronized multi-camera pipelines.
- 🧠 **Agentic AI & Cognitive Memory:** Building autonomous Multi-Agent Systems (MAS) with planning-first reasoning, dynamic skill routing, and long-term memory architectures (epistemic integrity, MCP & A2A protocols).
- ⚙️ **High-Performance Data Architecture:** Designing high-throughput data lakes (Databricks Delta Lake, Apache Spark) and semantic Knowledge Graphs (SPARQL, Jena Fuseki).
- 🏆 **Grand Prize Winner:** Microsoft Agent Hackathon (Tokyo Electron Device / Microsoft Enterprise Division) — Multi-sensor robot anomaly diagnostics achieving 0.95 F1-score.
- 🎓 **Background:** Computer Science graduate from Hanoi University of Science and Technology (**HUST K67**) with Distinction (CPA: 3.78/4.0); 2x National Mathematical Olympiad Prize Winner.

---

### 🛠️ Tech Stack Matrix

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,rust,ts,java,cpp,c,postgres,fastapi,docker,kubernetes,linux,git" alt="Core Technologies" /><br/><br/>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,scikitlearn,spark,kafka,dbt,react,tauri,html,css" alt="Frameworks & Tools" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Physical%20AI-SO--ARM--101%20%7C%20LeRobot%20%7C%20VLA-blueviolet?style=flat-square" alt="Physical AI"/>
  <img src="https://img.shields.io/badge/Agentic%20Systems-MCP%20%7C%20A2A%20%7C%20DSPy%20%7C%20LangChain-8A2BE2?style=flat-square" alt="Agents"/>
  <img src="https://img.shields.io/badge/Semantic%20Web-OWL2%20RL%20%7C%20SHACL%20%7C%20SPARQL%20%7C%20Jena-FF6F00?style=flat-square" alt="Semantic Web"/>
  <img src="https://img.shields.io/badge/Data%20Lake-Databricks%20%7C%20Delta%20Lake%20%7C%20Spark-E25A1C?style=flat-square" alt="Data Lake"/>
</p>

---

### 🚀 Featured Projects

Only repositories that are actively maintained are featured here. Archived work is listed separately at the bottom.

#### 🧠 Agentic AI, Memory & Local-First Systems

| Repository | Description | Topics |
|---|---|---|
| [**my-meta-brain**](https://github.com/triet4p/my-meta-brain) | Owner-controlled encrypted second brain for AI agents (.NET 10 / C# / WPF): owner-scoped MCP access over single-use tokens and named pipes, DPAPI + AES-256-GCM vault at rest, encrypted backup & restore, selection-scoped export, and content-schema migration with encrypted rollback points. **Active development.** | `agent-memory` `mcp` `dotnet` `security` |
| [**mosaic-slm**](https://github.com/triet4p/mosaic-slm) | Research framework for compute-aware multi-agent decision-making on one 16 GB consumer GPU: shared small language model, per-agent private memory (SQLite), and a shared temporal knowledge graph (Kùzu). **Phases 0–2 complete; Phase 3 memory implemented with 0.0% deterministic paired improvement (target ≥5% not met); serving, training and RL not started.** | `multi-agent` `slm` `temporal-kg` `research` |

#### 🌐 Knowledge Graphs & Desktop Intelligence

| Repository | Description | Topics |
|---|---|---|
| [**projecta**](https://github.com/triet4p/projecta) | Local-first Windows desktop knowledge workspace (Tauri v2, bundled local services): ontology-backed project graph, source-grounded notes, human-in-the-loop review of AI-extracted candidates, and evidence-backed queries without external runtime dependencies. **Projecta 1.0.0 released Oct 2026 (Windows 10/11 x64).** | `ontology` `knowledge-graph` `tauri-v2` `local-first` |

#### 🔬 Latent Space & Representation Learning

| Repository | Description | Topics |
|---|---|---|
| [**latent-anything**](https://github.com/triet4p/latent-anything) | Python framework treating latent space as a first-class object: PCA/UMAP/SAE introspection, steering vectors and activation patching, world-model planning lanes, and bounded-memory streaming pipelines. **v1.0.0 published on PyPI (Sep 2026)**; documented evidence is CPU/synthetic-workload scoped. | `latent-space` `interpretability` `pypi` `python` |
| [**anomaly-representation-learning**](https://github.com/triet4p/anomaly-representation-learning) | Self-supervised representation learning for hard multivariate time-series anomalies: masked prediction, EMA targets, contrastive objectives, and a reproducible benchmark harness. **Experimental; no verified accuracy claim.** | `time-series` `anomaly-detection` `self-supervised` `pytorch` |

#### 🛠️ Applied Products & Research Tooling

| Repository | Description | Topics |
|---|---|---|
| [**aegis-f**](https://github.com/triet4p/aegis-f) | Offline-first personal Android expense tracker (Kotlin, Room/SQLite, ONNX): exact whole-dong VND ledger, optional bank-notification review inbox where every bank-derived record needs explicit confirmation, and on-device category suggestions applied only with explicit user acceptance. **In development; no public release.** | `android` `kotlin` `on-device-ml` `offline-first` |
| [**daily-research**](https://github.com/triet4p/daily-research) | AI research publishing platform (Next.js 16, TypeScript, Tailwind v4, MDX): overview, weekly and deep-dive tiers with bidirectional cross-references, plus RSS and Microsoft Teams tooling. | `nextjs` `mdx` `research` `typescript` |
| [**coding-agent-stacks**](https://github.com/triet4p/coding-agent-stacks) | Reusable rules, skills and subagent definitions for coding-agent workflows, shipped with a PowerShell installer. Configuration payload — not an agent runtime. | `agentic-ai` `developer-tools` `powershell` |
| [**triet4p.github.io**](https://github.com/triet4p/triet4p.github.io) | Personal portfolio site (React 19, TypeScript, Vite) publishing the projects and write-ups linked from this profile. | `portfolio` `react` `typescript` `vite` |

---

### 📦 Archived Projects

These repositories are archived and no longer maintained. They are kept as a record, not as current work.

<details>
<summary><b>Discontinued experiments & products (archived)</b></summary>

| Repository | What it was |
|---|---|
| [**cogmem**](https://github.com/triet4p/cogmem) | Cognitively grounded long-term memory API with typed memory networks and hybrid retrieval |
| [**arch-lens-ai**](https://github.com/triet4p/arch-lens-ai) | Desktop R&D operating system for technical due diligence (Tauri v2 + React 19) |
| [**paper-kg-ontology**](https://github.com/triet4p/paper-kg-ontology) | Research-paper knowledge graph lab: OWL2 RL reasoning, TDB2, SHACL validation |
| [**ecommerce-agent-databricks**](https://github.com/triet4p/ecommerce-agent-databricks) | Support agent on Databricks Apps with Lakebase, MLflow ResponsesAgent and governed tools |
| [**llm-serving-lab**](https://github.com/triet4p/llm-serving-lab) | vLLM / Ollama / FastAPI serving benchmarks behind an OpenAI-compatible client |
| [**claw-code-explain**](https://github.com/triet4p/claw-code-explain) | 12 agentic harness patterns — Claude Code internals explained |
| [**bridge-research**](https://github.com/triet4p/bridge-research) | Desktop AI research assistant (Tauri + React + FastAPI) |
| [**math-ai-connect**](https://github.com/triet4p/math-ai-connect) | Mathematics and AI learning journal (Astro + MDX) |
| [**cognition**](https://github.com/triet4p/cognition) | Rust cognitively grounded agent memory system, extended into an agent architecture |
| [**aegis-ma**](https://github.com/triet4p/aegis-ma) | A2A (Agent-to-Agent) SDK prototype over JSON-RPC/WebSocket |
| [**itapia**](https://github.com/triet4p/itapia) | Explainable AI co-pilot for retail investors |
| [**mcp-fin-test**](https://github.com/triet4p/mcp-fin-test) | Financial agent built on the Model Context Protocol |
| [**otto-rec-sys**](https://github.com/triet4p/otto-rec-sys) | Recommendation-system solution for the OTTO competition |
| [**ez_cli**](https://github.com/triet4p/ez_cli) | Rust CLI utilities for learning and performance testing |
| [**excel2md**](https://github.com/triet4p/excel2md) | Layout-preserving Excel to Markdown converter for Windows |
| [**magma_obby**](https://github.com/triet4p/magma_obby) | Flutter game deployed to iOS via Codemagic |

</details>

<details>
<summary><b>Earlier study & competition archives (archived)</b></summary>

| Repository | What it was |
|---|---|
| [**app-log-process-k8s**](https://github.com/triet4p/app-log-process-k8s) | Big-data pipeline (Hadoop, Spark, Kafka, Hive, dbt) processing application logs |
| [**SeEvoDJSSP**](https://github.com/triet4p/SeEvoDJSSP) | Self-evolution algorithm applied to the dynamic job shop scheduling problem |
| [**KaggleCompetition**](https://github.com/triet4p/KaggleCompetition) | Collection of Kaggle competition solutions |
| [**SearchAppQt**](https://github.com/triet4p/SearchAppQt) | Qt app visualizing linear and binary search algorithms |
| [**NoteApp**](https://github.com/triet4p/NoteApp) | Simple desktop app for taking and sharing notes |

</details>

---

### 📈 GitHub Stats & Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=triet4p&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api?username=triet4p&show_icons=true&theme=default&include_all_commits=true" />
    <img alt="Triet's GitHub Stats" src="https://github-stats-extended.vercel.app/api?username=triet4p&show_icons=true&theme=tokyonight&include_all_commits=true" height="165" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=triet4p&theme=tokyonight&hide_border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=triet4p&theme=default" />
    <img alt="GitHub Streak" src="https://streak-stats.demolab.com/?user=triet4p&theme=tokyonight" height="165" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=triet4p&layout=compact&theme=tokyonight&hide_border=true&hide=html,tex,makefile" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=triet4p&layout=compact&theme=default&hide=html,tex,makefile" />
    <img alt="Top Languages" src="https://github-stats-extended.vercel.app/api/top-langs/?username=triet4p&layout=compact&theme=tokyonight&hide_border=true&hide=html,tex,makefile" height="150" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/triet4p/triet4p/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/triet4p/triet4p/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/triet4p/triet4p/output/github-contribution-grid-snake.svg" />
  </picture>
</p>
