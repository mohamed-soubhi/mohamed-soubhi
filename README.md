# Hi, I'm Mohamed Soubhi

**Senior Automotive Software Engineer** — bridging safety-critical embedded systems and graph data science.

11+ years building automotive software at **Valeo**, **TTTech Auto**, and **Concentrio AG**.
Currently applying **Neo4j Graph Data Science** and **Python** to automotive software validation at scale.

🌐 **[mohamed-soubhi.github.io](https://mohamed-soubhi.github.io)** · 💼 [LinkedIn](https://www.linkedin.com/in/mohamed-soubhi) · 📊 [Kaggle](https://www.kaggle.com/mohamedsoubhi)

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

### [Fraud Graph Demo](https://github.com/mohamed-soubhi/fraud-graph-demo)

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

**GNN Layer** — 3-layer GraphSAGE trained on GDS properties as node features
→ writes `fraudProb ∈ [0,1]` to every account · ensemble with rules maximises recall

**Fraud Rules** — 3 Cypher pattern queries: velocity (>3 txns in 10 steps) · mule chain (A→B→C→cashout) · balance drain (≥95% emptied)

**Benchmark** — WCC 20ms · sampled Betweenness 142× faster than exact · PageRank converges in 2 iterations

---

## Career

```
2023 – Present  │ Concentrio AG (Madrid)    │ Senior Software Engineer · AUTOSAR · Graph Data Science
2021 – 2023     │ TTTech Auto (Madrid)      │ Safety Embedded SW Engineer · Motionwise / HIP32G
2017 – 2021     │ Valeo (Cairo)             │ Senior Embedded SW Engineer · Powertrain Systems
2015 – 2016     │ BioBusiness (Cairo)       │ Embedded SW Engineer · Medical Devices
```

---

*Madrid, Spain · EU Work Permit · Open to SDV, automotive data validation, and Edge AI roles*
