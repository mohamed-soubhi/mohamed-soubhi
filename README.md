# Hi, I'm Mohamed Soubhi 👋

**Senior Automotive Software Engineer** — bridging safety-critical embedded systems and graph data science.

🟢 **Open to new opportunities** — AUTOSAR/embedded roles and AI/data automation roles

13+ years building automotive software at **Valeo**, **TTTech Auto**, and **Concentrico**.
Currently applying **Neo4j Graph Data Science** and **Python** to automotive software validation at scale.

🌐 **[mohamed-soubhi.github.io](https://mohamed-soubhi.github.io)** · 💼 [LinkedIn](https://www.linkedin.com/in/mohamed-soubhi) · 📊 [Kaggle](https://www.kaggle.com/mohamedsoubhi) · 📧 [eng.mohamed.soubhi@gmail.com](mailto:eng.mohamed.soubhi@gmail.com) 

---

## What I Work On

- **AUTOSAR** embedded software (BSW / RTE / ASW) on ARM Cortex-M7 and AURIX TC3xx
- **Functional Safety** — ASIL B, ISO 26262, ASPICE Level 4
- **Graph-based software validation** — Neo4j signal-flow analysis for automotive code quality
- **Data pipelines** for automotive software analysis (Python, Pandas, Docker)
- **Diagnostic software** — UDS / ISO 14229-1, CANalyzer, Davinci Configurator

---

## Stack

**Embedded**

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![ARM](https://img.shields.io/badge/ARM_Cortex--M7-0091BD?style=flat&logo=arm&logoColor=white)
![AUTOSAR](https://img.shields.io/badge/AUTOSAR-003B6E?style=flat)
![MISRA](https://img.shields.io/badge/MISRA--C-555?style=flat)

**Data Science**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

**Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)

---

## Featured Projects

### ⚡ Modern C++ & Embedded Systems Study Portal

[![Live Portal](https://img.shields.io/badge/🌐_Live_Portal-Interactive_App-10b981?style=for-the-badge&logo=github)](https://github.com/mohamed-soubhi/Embedded-Cpp-study-portal)
[![Projects](https://img.shields.io/badge/Projects-116_Deep--Dives-38bdf8?style=for-the-badge&logo=c%2B%2B)](https://github.com/mohamed-soubhi/Embedded-Cpp-study-portal)
[![Quizzes](https://img.shields.io/badge/MCQ_Quizzes-464_Questions-a855f7?style=for-the-badge)](https://github.com/mohamed-soubhi/Embedded-Cpp-study-portal)
[![Target](https://img.shields.io/badge/Target-ARM_Cortex--M_%7C_MISRA-ef4444?style=for-the-badge&logo=arm)](https://github.com/mohamed-soubhi/Embedded-Cpp-study-portal)

An interactive web companion covering **116 course projects** across 12 sections of Modern C++ (C++11/14/17/20), translated into bare-metal embedded systems architectures:

- 💻 **Annotated Source Code** — full syntax-highlighted viewers with multi-file tabs
- ⚡ **Embedded Hardware Realities** — ARM Cortex-M AAPCS calling conventions, instruction pipelines, struct padding, LittleFS, DMA framebuffers, MMIO wrappers
- 💡 **Zero-Overhead Refactoring** — production-ready, deterministic, MISRA-compliant modern C++ design patterns
- 🧠 **464 Interactive Quizzes** — instant self-checking questions with technical explanations

👉 **[Explore the Live Portal](https://mohamed-soubhi.github.io/The-Complete-Cpp-Developer-Course/)** · 📂 **[View Source Code](https://github.com/mohamed-soubhi/The-Complete-Cpp-Developer-Course)**

---

### 🕵️ Fraud Graph Demo

[![Repo](https://img.shields.io/badge/📂_Repo-View_Source-24292e?style=for-the-badge&logo=github)](https://github.com/mohamed-soubhi/fraud-graph-demo)

End-to-end fraud detection knowledge graph on PaySim synthetic transactions (50k rows).
Neo4j 5 + GDS 2.13 · GraphSAGE GNN · LangChain NL→Cypher · Ollama Cloud (`deepseek-v4-flash`)

![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)

**GDS Algorithm Pipeline** — Account→Account virtual graph projection:

| Node Property | Algorithm | Fraud Signal |
|---|---|---|
| `community` | Louvain | High-fraud-density clusters |
| `pageRank` | PageRank | Central money-hub accounts |
| `wccComponent` | WCC | Isolated fraud rings |
| `betweenness` | Betweenness Centrality | Bridge / relay accounts |
| `triangleCount` | Cycle Detection (Cypher) | Circular layering flows (A→B→C→A) |

**GNN Layer** — 3-layer GraphSAGE trained on GDS properties as node features → writes `fraudProb ∈ [0,1]` to every account · ensemble with rules maximises recall

**Fraud Rules** — 3 Cypher pattern queries: velocity (>3 txns in 10 steps) · mule chain (A→B→C→cashout) · balance drain (≥95% emptied)

**Benchmark** — WCC 20ms · sampled Betweenness 142× faster than exact · PageRank converges in 2 iterations

---


## 📫 Get in Touch

💼 [LinkedIn](https://www.linkedin.com/in/mohamed-soubhi) · 📧 [eng.mohamed.soubhi@gmail.com](mailto:eng.mohamed.soubhi@gmail.com)  · 🌐 [Portfolio](https://mohamed-soubhi.github.io)
