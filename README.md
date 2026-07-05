<div align="center">

# Muhammad Ibtasaam Amjad

<img src="https://readme-typing-svg.demolab.com/?lines=CS+Undergrad+%40+FAST-NUCES;AI+%2F+Agentic+Systems+Engineer;Founder+%C2%B7+Builder+%C2%B7+Game+Developer;Architecting+Kybernetes+%26+Maktaba&font=Fira+Code&center=true&width=580&height=40&color=58A6FF&vCenter=true&size=22" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-ibtasaam-amjad/)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=flat&logo=Instagram&logoColor=white)](https://instagram.com/mughal_ibtasaam)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:ibtasaam.mughal@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Mughal-Hash-24)

![Profile Views](https://komarev.com/ghpvc/?username=Mughal-Hash-24&color=58A6FF&style=flat&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/Mughal-Hash-24?label=Followers&style=flat&color=58A6FF)

</div>

---

## About Me

CS undergrad at **FAST-NUCES, Islamabad (Batch '28)**, building at the intersection of agentic AI systems, distributed/decentralized architecture, and low-level systems programming.

I currently serve as a **Teaching Assistant** for Object-Oriented Programming and as **Technical Projects Officer** at the **FAST Artificial Intelligence Society**, where I design LangChain + n8n automation pipelines deployed for university-wide use. Outside coursework, I'm building **Kybernetes** — a 10-layer agentic note-taking system — and **Maktaba**, a living-library web app built on a 650,000+ word personal knowledge vault spanning CS, philosophy, history, and Islamic jurisprudence.

I learn by shipping — from Solidity smart contracts and genetic algorithms to x86 assembly and 10+ games in Python/pygame and C++/SFML.

---

## Currently Building

Pulled directly from the repos — real commit history, real language breakdowns, no filler.

### 🧠 [Musannif](https://github.com/Mughal-Hash-24/Musannif) *(the repo behind "Kybernetes")*
Structured long-form document generator — an agentic system that turns a short prompt into a fully-cited, narratively coherent long-form document, built to eliminate the redundant re-telling of the same facts/stories across sections.

- **Architecture**: heading-based AST as the canonical document structure — the markdown heading hierarchy *is* the dependency graph, with `depends_on` edges between deterministic AST node addresses (no embeddings, no similarity thresholds)
- **Sub-agents**: a fleet of domain agents named after classical polymaths — `ibnkhaldun`, `machiavelli`, `nabokov`, `iqbal`, `turing`, `davinci`, `alhaytham` — dispatched in parallel across document sections
- **Live telemetry** (from `subagent_stats.json`): **1,248 LLM calls**, ~4.37M input tokens, ~2.5M output tokens processed across runs so far
- **Stack**: Python 3.12, Anthropic SDK, `networkx` for the dependency graph, `textual` for a full TUI, `typer` CLI
- **Stats**: 16 commits · ~12K lines of code (Python + docs) · CLI + TUI shipped, test suite in place

### 🌐 [Proxenos](https://github.com/Mughal-Hash-24/proxenos)
B2B trade orchestration platform bridging decentralized finance and physical logistics — the largest codebase of the three, split into three independently-versioned subsystems.

- **`proxenos-core`** — Java 21 / Spring Boot service layer (largest single-language footprint: 21K+ lines of Java)
- **`proxenos-ai`** — Python services including a `neat_engine` (NEAT genetic algorithm) solving the multi-constraint multi-modal logistics problem
- **`proxenos-contracts`** — Solidity `Escrow.sol` on a Ganache testnet, wired through Web3j for dual-key escrow settlement, replacing traditional Letter-of-Credit latency
- **Infra**: Dockerized Postgres + Ganache, Make/PowerShell cross-platform bootstrap scripts, Maven + Hardhat test pipelines
- **Stats**: 56 commits · ~55K lines across 17 languages (Java, Python, Solidity, PlantUML, FXML, Shell, PowerShell) · full SRD + implementation-summary docs in-repo

### 📚 [Maktaba](https://github.com/Mughal-Hash-24/Maktaba) + Hikma
A living-library web app over a 650,000+ word personal Obsidian vault (CS, philosophy, history, Islamic jurisprudence), named after Bayt al-Hikma.

- **Frontend**: Next.js 15 (Turbopack) + React 19, with a client-side `agent-harness.ts` powering **Hikma**, the AI research companion
- **Bring-your-own-key**: `ApiKeyManager.tsx` stores API keys client-side, no server-side key custody
- **Knowledge graph**: `react-force-graph-2d`-powered "Night Sky" graph over the vault
- **Search & content pipeline**: `remark`/`rehype` markdown pipeline with KaTeX math and syntax highlighting, `pagefind` static search, `@huggingface/transformers` for in-browser embeddings, Supabase for auth/storage
- **Stats**: 15 commits · ~22K lines of code, dominated by TypeScript (8.2K) and CSS (4K)

### Also on the resume
- 📄 **DocuMind** — Dual-stage RAG pipeline (n8n + LlamaParse + Pinecone + Gemini 1.5 Pro) for high-precision, page-cited PDF question answering, with a Next.js "Semantic Sync" viewer
- 🎓 **EduGap** — Socratic Tutor + Curriculum-to-Job-Market Gap Analyzer on a custom agent harness with persistent memory and an Obsidian-style React Flow concept graph

---

## Experience

**Teaching Assistant** — FAST, Islamabad Campus · *Jan 2026 – Present*
Designed and evaluated OOP coursework, delivering code reviews and technical mentorship on core computing and software design.

**Technical Projects Officer** — FAST Artificial Intelligence Society · *Jan 2026 – Present*
Engineered automated workflows with LangChain and n8n, integrating code-based AI environments with visual node systems and deploying them for university-wide use.

**Lead Organizer, "Deadshot" Esports Tournament** — FAST-NUCES · *Mar 2026 – Present*
Directed a section-wide competitive gaming tournament, designing an auction-draft player selection system and tracking performance metrics for fair play.

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Assembly](https://img.shields.io/badge/x86_ASM-%23000000.svg?style=for-the-badge&logo=assemblyscript&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)

**AI / Agentic Systems**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

**Web, Backend & Infra**
![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Tools & Platforms**
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7)
![Render](https://img.shields.io/badge/Render-%2346E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

**Design**
![Illustrator](https://img.shields.io/badge/Illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white)
![Photoshop](https://img.shields.io/badge/Photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)

---

## GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Mughal-Hash-24&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mughal-Hash-24&layout=compact&theme=radical&hide_border=true&hide=html&langs_count=8" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Mughal-Hash-24&theme=radical&hide_border=true" />

<img src="https://github-profile-trophy.vercel.app/?username=Mughal-Hash-24&theme=radical&no-frame=true&margin-w=8&row=1" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Mughal-Hash-24&theme=react-dark&hide_border=true" width="100%" />

</div>

---

## Featured Repositories

<div align="center">

<a href="https://github.com/Mughal-Hash-24/Musannif"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Mughal-Hash-24&repo=Musannif&theme=radical&hide_border=true" /></a>
<a href="https://github.com/Mughal-Hash-24/proxenos"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Mughal-Hash-24&repo=proxenos&theme=radical&hide_border=true" /></a>
<a href="https://github.com/Mughal-Hash-24/Maktaba"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Mughal-Hash-24&repo=Maktaba&theme=radical&hide_border=true" /></a>
<a href="https://github.com/Mughal-Hash-24/Chess"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Mughal-Hash-24&repo=Chess&theme=radical&hide_border=true" /></a>

</div>

### Codebase breakdown (measured directly from source, `cloc`)

| Repo | Commits | Lines of Code | Top Languages |
|---|---|---|---|
| **Musannif** (Kybernetes) | 16 | ~12,000 | Markdown, Python |
| **proxenos** | 56 | ~54,800 | Java, Markdown, JSON, FXML |
| **Maktaba** | 15 | ~22,300 | JSON, TypeScript, CSS |

---

## Let's Connect

Open to collaborating on agentic AI systems, decentralized infrastructure, or interesting technical problems in general.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-%230077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/muhammad-ibtasaam-amjad/)
[![Email](https://img.shields.io/badge/Email-Say%20Hi-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ibtasaam.mughal@gmail.com)

<sub>Based in Rawalpindi/Islamabad, Pakistan 🇵🇰 · Open to remote collaboration worldwide</sub>

</div>
