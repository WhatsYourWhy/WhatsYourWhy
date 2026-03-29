<div align="center">

# Justin Shank

```text
██╗    ██╗██╗  ██╗██╗   ██╗
██║    ██║██║  ██║╚██╗ ██╔╝
██║ █╗ ██║███████║ ╚████╔╝
██║███╗██║██╔══██║  ╚██╔╝
╚███╔███╔╝██║  ██║   ██║
 ╚══╝╚══╝ ╚═╝  ╚═╝   ╚═╝

      WHAT'S YOUR WHY
```

𝑊 ℎ 𝑎 𝑡 𝑠 𝑌 𝑜 𝑢 𝑟 𝑊 ℎ 𝑦  
**WhatsYourWhy**

Here be monsters & analytics. I build deterministic tools for messy problems—whether that’s supply chain resilience, ADHD ritual cards, or gamma-ray bursts.
Each project lives in its own world, but they all share a few signals: **offline-first**, **explainable**, **operationally-reliable**, and always pushing back on black-box hype.
If those resonate, grab a torch and explore.

<img src="https://raw.githubusercontent.com/WhatsYourWhy/WhatsYourWhy/main/assets/banner_monster.gif" alt="Banner showing a dragon juggling supply chains and notebooks" width="100%"/>

</div>

## 🌐 Navigation

| Stack | Who it helps | Core repos |
|---|---|---|
| Supply Chain & Operational Risk | Enterprise logistics teams and ops leaders who need deterministic, auditable alerts and brand automation | Hardstop, Lumina-Pro, Alert-Axolotl-Evo |
| Neurodivergence & Knowledge Management | ADHD/ND folks, knowledge workers, and researchers who live in notes and need more humane tooling | Dragons & Distractions, Journey-Log, Strainer-CLI, Obsidian extensions, Psi-Loop |
| Cognitive & AI Safety | Researchers exploring how to build safer AI & cognitive tools, emphasizing transparency over magic | TopoGuard, The Temporal Gradient, Information-Causality Note |
| Bio & Signal Processing | Biologists and physicists who need reproducible analysis pipelines | Biological-Data-OS, GRBToolkit |
| Playful Experiments | Artists and curious tinkerers | Thresholds, Zero Terminal, Seralyth Menu |
| Business & Web | Clients and collaborators looking for my professional services and websites | Shank Strategy Ops Web, whatsyourwhy.github.io, dragons-and-distractions-card-preview |

## Determinism & Local-First

I’m obsessed with deterministic systems: given the same inputs, they always produce the same outputs.
Hardstop scores supply-chain events in a reproducible way, persisting state on your file system rather than a hidden SaaS—no network, no subscription, no surprises.

This ethos runs through everything:
- Strainer-CLI summarizes text files offline.
- Psi-Loop scores candidate contexts based on novelty and value without external services.
- Cognitive Glow logs note accesses in Obsidian to compute a simple glow score.

## Transparent & Auditable

Supply chains collapse when nobody knows why an alert fired.
Hardstop and Alert-Axolotl-Evo produce auditable scores and rule trees so you can trace exactly how a decision was made.
Biological-Data-OS logs every step of ingestion, canonicalization, and semantic resolution, with lineage queries for every piece of data.
GRBToolkit includes Jupyter notebooks, scripts, and CSVs so you can reproduce time-frequency analyses of gamma-ray bursts.

## Reliability & Self-Evaluation

Tools should fail loudly rather than silently:
- Hardstop returns exit codes indicating whether new alerts were raised, suppressed, or timed out.
- Alert-Axolotl-Evo evolves symbolic rules with fitness functions aligned to false-positive rates and detection precision.
- Psi-Loop includes regression tests and benchmark scripts for its ranking algorithm.

## 📦 Projects

### Supply Chain & Operational Risk

#### Hardstop
A deterministic risk engine that monitors news feeds, government data, and other sources to flag supply-chain disruptions.
Hardstop uses suppression rules to avoid alert fatigue, links events to your internal network (facilities, shipments, lanes), and stores everything locally.
Exit codes let you embed it in larger automations—no hidden heuristics, no black boxes.

#### Lumina-Pro
An AI brand-studio workspace: it combines automated market analysis, generative design, supply-chain monitoring, and even voice pitch coaching.
Built with React/Tailwind CSS on the frontend and Express/Supabase on the backend, Lumina-Pro generates PDF reports, runs offline, and includes integrated tests.

#### Alert-Axolotl-Evo
A deterministic genetic-programming system for anomaly detection.
It evolves explicit logic trees under economic constraints, optimizing for interpretability and precision.
Fitness metrics align with your cost of false positives and false negatives, and self-evaluation routines provide run-level exit codes for continuous integration.

### Neurodivergence & Knowledge Management

#### Dragons & Distractions
A monster-themed ADHD support project.
The dragons-and-distractions-site houses a Jekyll site with printable ritual cards and metadata scripts.
The dragons-and-distractions-card-preview repo hosts a stand-alone GitHub Pages build for previewing finished card decks.

#### Journey-Log
A local-storage checklist with categories, moods, priorities, quotes, and backup/restore.
You can filter tasks, undo bulk actions, and explore insights—all in your browser with no server.

#### Strainer-CLI
Offline summarization for `.txt` and `.md` files.
Strainer extracts key sentences, computes tags, metrics, and optional evidence anchors.
Choose between a Fast keyword-based mode or a Smart embedding-based mode.

#### Obsidian & Note Tools
- **Cognitive Glow** – Tracks note openings in Obsidian, computes a glow score based on recency and frequency, and presents top notes in a sidebar.
- **Obsidian Spotify Link** – Inserts your currently playing track into notes, fetches daily history, and supports custom templates.
- **Obsidian Releases Mirror** – A fork of the Obsidian plugin/theme registry enabling offline packaging and deterministic dependency management.

#### Psi-Loop
A research library exploring retrieval rankings that prefer useful and non-redundant context.
Psi0 ranks candidates by value relative to the goal and novelty relative to what you already have.
It exposes pluggable embedders and sources and includes benchmark scripts to compare against similarity-only baselines.

### Cognitive & AI Safety

#### TopoGuard
A formal verification framework for prompt injections (topological attack detection).
See the repository for details on how it models state transitions and proves safety properties (work in progress).

#### The Temporal Gradient
A research notebook exploring time-weighted attention mechanisms and memory consolidation for agents.
It contains interactive experiments on signal decay, retrieval order, and forgetting curves (work in progress).

#### Information-Causality Note
A reading note and set of exercises on information-theoretic causality for AI systems.
It collects proofs, definitions, and open questions.

### Bio & Signal Processing

#### Biological-Data-OS
A FastAPI/SQLAlchemy reference implementation for deterministic biological data ingestion, semantic resolution, and lineage-backed trust workflows.
It exposes REST routes for ingestion, sources, canonical records, semantic assertions, review, lineage, and workflows.
The codebase includes extensive tests, migration scripts, and docs on ingestion, canonicalisation, and review workflows.

#### GRBToolkit
A modular signal simulation and analysis suite for gamma-ray burst light curves.
It supports synthetic models (QPIX, FRED), real Fermi data, Bayesian block sweeps, Wavelet Z (WWZ) computation, and model comparison using AIC.
The toolkit emphasizes reproducibility: scripts produce CSVs and figures, notebooks capture analyses, and citation guidelines ensure proper credit.

### Playful Experiments

#### Thresholds
An unfinished digital doorway disguised as a GitHub repository.
It contains a portal page, generative sigils, a manifest of states, and hidden base64 keys.
The project is as much about the mood of an abandoned experiment as it is about code—if you like liminal spaces and cryptic YAML, explore.

#### Zero Terminal
A terminal-themed personal website where you navigate by typing commands instead of clicking links.
It includes a virtual file system, CRT effects, and 30 commands that map to blog posts, projects, and life statuses.
Built with vanilla JS + Vite and deployable via Vercel.

#### Seralyth Menu
An open-source mod menu for the VR game Gorilla Tag.
Forked to champion community modding, it offers a feature-packed interface and calls out the GPL license to keep mods free and accessible.

### Business & Web

#### Shank Strategy Ops Web
The official website for Shank Strategy Ops LLC.
It runs on React 19 + Vite with an Express backend and includes advanced UI/UX, Radix UI, Tailwind styling, and serverless contact forms.
Strategic documents in the repo (`EngagementModel.md`, `ideas.md`, `AGENTS.md`) outline how the business works and integrate AI agent configuration.

#### whatsyourwhy.github.io & Card Previews
- **whatsyourwhy.github.io** – Houses my personal site; see *Zero Terminal* for the theme.
- **dragons-and-distractions-card-preview** – A prebuilt GitHub Pages site to review printed ritual cards separately from the main site.

## ✍️ Work With Me

I run Shank Strategy Ops, where I bring execution leadership to complex projects across supply chain, knowledge management, and AI safety.
If you need deterministic tools that won’t gaslight your auditors, drop me a line or try the `contact` command in Zero Terminal.

Thanks for visiting.
May your data be structured, your alerts be meaningful, and your dragons be friendly.
