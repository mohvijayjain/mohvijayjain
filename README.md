<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0F172A,50:1E3A8A,100:0EA5E9&text=Mohvijay%20Jain&fontColor=ffffff&fontSize=52&fontAlignY=36&animation=fadeIn&desc=AI%20%26%20ML%20Engineer%20%7C%20Building%20Scalable%2C%20Production-Ready%20AI%20Systems&descSize=17&descAlignY=58"/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=38BDF8&center=true&vCenter=true&width=700&lines=RAG+systems+with+0.85+faithfulness;Self-healing+ML+pipelines;LLM+apps+grounded+in+real+data;Shipping+end-to-end%2C+not+just+notebooks"/>

<br/>

<a href="https://www.linkedin.com/in/mohvijayjn/"><img src="https://skillicons.dev/icons?i=linkedin" height="40" alt="LinkedIn"/></a>&nbsp;
<a href="mailto:mohvijayjain12@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="40" alt="Email"/></a>&nbsp;
<a href="https://github.com/mohvijayjain"><img src="https://skillicons.dev/icons?i=github" height="40" alt="GitHub"/></a>

<br/><br/>

<img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20AI%2FML%20INTERNSHIPS-22C55E?style=for-the-badge&labelColor=0F172A"/>
<img src="https://img.shields.io/badge/BASED%20IN-INDIA-0EA5E9?style=for-the-badge&labelColor=0F172A"/>
<img src="https://img.shields.io/badge/AWS-CERTIFIED-FF9900?style=for-the-badge&labelColor=0F172A"/>

</div>

<br/>

```python
from dataclasses import dataclass, field


@dataclass
class Mohvijay:
    role:       str  = "AI/ML Engineer"
    education:  str  = "B.Tech CSE (Data Science) @ Bennett University"
    builds:     list = field(default_factory=lambda: ["RAG systems", "LLM apps", "MLOps pipelines"])
    principles: list = field(default_factory=lambda: ["grounded answers", "measurable quality", "ship it"])

    def currently_learning(self) -> list:
        return ["LangGraph", "multi-agent workflows"]

    def open_to(self) -> str:
        return "AI/ML & GenAI internships 🚀"


me = Mohvijay()
print(me.open_to())  # AI/ML & GenAI internships 🚀
```

---

## 🛡️ Featured: Sentinel-AI

**A self-healing ML platform.** It watches a production model, figures out whether incoming data drift actually hurts predictions, retrains only when it matters, and uses an LLM to explain every decision in plain English.

```mermaid
flowchart LR
    A[Production data] --> B[Drift detection<br/>PSI, KS, Jensen-Shannon]
    B --> C{SHAP: does drift<br/>hurt predictions?}
    C -- No --> D[Monitor in Grafana]
    C -- Yes --> E[Prefect retrains<br/>challenger model]
    E --> F{Quality gates}
    F -- Pass --> G[Promote via MLflow]
    F -- Fail --> H[Keep champion]
    D --> I[RAG assistant on Nemotron<br/>explains what happened]
    G --> I
    H --> I
```

<table>
<tr>
<td align="center"><b>6.9M+</b><br/><sub>records</sub></td>
<td align="center"><b>R² ≈ 0.86</b><br/><sub>trip duration model</sub></td>
<td align="center"><b>MAE ≈ 3.3 min</b><br/><sub>prediction error</sub></td>
<td align="center"><b>3</b><br/><sub>drift tests combined</sub></td>
</tr>
</table>

<img src="https://img.shields.io/badge/LightGBM-02569B?style=flat-square"/> <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white"/> <img src="https://img.shields.io/badge/Prefect-070E10?style=flat-square&logo=prefect&logoColor=white"/> <img src="https://img.shields.io/badge/Evidently%20AI-4F46E5?style=flat-square"/> <img src="https://img.shields.io/badge/NVIDIA%20Nemotron-76B900?style=flat-square&logo=nvidia&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

👉 **[View repository](https://github.com/mohvijayjain/Sentinel-AI)**

---

## 📚 More Projects

<table>
<tr>
<td width="50%" valign="top">

### ScholarRAG
Grounded Q&A over research papers. Parses PDFs section by section, answers with page-level citations, and refuses when the evidence isn't there.

**0.85** faithfulness · **1.0** context recall (RAGAS)

<sub>LangChain · ChromaDB · BGE · NVIDIA NIM · FastAPI</sub>

👉 **[View repository](https://github.com/mohvijayjain/ScholarRAG)**

</td>
<td width="50%" valign="top">

### GeoSight
Land cover classification and road network analysis across 5 Indian states from satellite imagery, with zero manual labeling.

**97.79%** pixel accuracy · **0.9154** mIoU · **66K+** tiles

<sub>Python · Remote sensing · Graph theory</sub>

👉 **[View repository](https://github.com/mohvijayjain/GeoSight)**

</td>
</tr>
</table>

---

## 🧰 Toolkit

| | |
|:---|:---|
| **Languages** | <img src="https://skillicons.dev/icons?i=python,cpp,c&perline=8" height="32"/> |
| **GenAI / LLM** | `RAG` `LangChain` `ChromaDB` `NVIDIA NIM` `RAGAS` `Prompt Engineering` |
| **ML** | `Scikit-learn` `LightGBM` `Optuna` `SHAP` `Pandas` `NumPy` |
| **MLOps** | `MLflow` `Prefect` `Evidently AI` `Prometheus` `Grafana` |
| **Backend & Cloud** | <img src="https://skillicons.dev/icons?i=fastapi,docker,postgres,mysql,aws,git,linux&perline=8" height="32"/> |

---

## 🏆 Highlights

- ☁️ **AWS Certified Cloud Practitioner**
- 🚀 **Perplexity AI Campus Ambassador** at Bennett University
- 💡 **Smart India Hackathon** Inter-College Round: Rank **61 / 561**

---

<div align="center">

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=24&pause=1500&color=38BDF8&center=true&vCenter=true&width=700&lines=Building+something+with+LLMs+or+MLOps%3F;Let's+build+it+together."/>

<br/><br/>

<a href="mailto:mohvijayjain12@gmail.com"><img src="https://img.shields.io/badge/EMAIL%20ME-mohvijayjain12%40gmail.com-EA4335?style=for-the-badge&labelColor=0F172A"/></a>
<a href="https://www.linkedin.com/in/mohvijayjn/"><img src="https://img.shields.io/badge/CONNECT-LinkedIn-0A66C2?style=for-the-badge&labelColor=0F172A"/></a>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0EA5E9,50:1E3A8A,100:0F172A&height=150&section=footer&text=Thanks%20for%20stopping%20by&fontSize=26&fontColor=ffffff&fontAlignY=72&animation=twinkling"/>

</div>
