<!-- ═══════════════ HEADER ═══════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:0d1117,50:00ff9c,100:0d1117&height=220&section=header&text=Shubham%20Yedekar&fontSize=58&fontColor=ffffff&animation=fadeIn&desc=I%20build%20agents%20that%20think%2C%20act%20%26%20ship&descAlignY=72&descSize=18" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=00FF9C&center=true&vCenter=true&width=640&lines=%3E+initializing+agent...;%3E+loading+tools%3A+python%2C+pytorch%2C+langchain;%3E+connecting+MCP+servers...+%E2%9C%93;%3E+status%3A+ready+to+build+something+wild" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shubham-yedekar-8a2a141b7/"><img src="https://img.shields.io/badge/LinkedIn-connect-00ff9c?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117"/></a>
  <img src="https://komarev.com/ghpvc/?username=ShubhamRSY&label=profile%20views&color=00ff9c&style=for-the-badge&labelColor=0d1117" />
</p>

---

### `$ cat whoami.py`

```python
from dataclasses import dataclass, field

@dataclass
class Agent:
    name: str = "Shubham Yedekar"
    role: tuple = ("ML Engineer", "Agentic AI Developer")
    system_prompt: str = "Turn messy data and vague ideas into AI that actually ships."

    tools: dict = field(default_factory=lambda: {
        "languages":  ["Python", "TypeScript", "SQL"],
        "ml":         ["PyTorch", "TensorFlow", "scikit-learn"],
        "agents":     ["LangChain", "MCP", "tool-calling LLMs"],
        "backend":    ["FastAPI", "Docker"],
        "cloud":      ["AWS", "Linux"],
    })

    memory: list = field(default_factory=lambda: [
        "currently_exploring -> multi-agent systems & Model Context Protocol",
        "currently_building  -> agentic analytics pipelines",
        "always_learning     -> scalable, production-grade AI infra",
    ])

    def run(self, problem):
        return self.plan(problem) | self.act() | self.evaluate() | self.ship()

me = Agent()
```

---

### 🧠 How I build agents

```mermaid
flowchart LR
    U([👤 User intent]) --> P{{🧭 Planner LLM}}
    P -->|decompose| T1[🔧 Tool: SQL / APIs]
    P -->|retrieve| T2[📚 RAG / Vector store]
    P -->|connect| T3[🔌 MCP servers]
    T1 & T2 & T3 --> R[⚙️ Reasoning loop]
    R -->|self-check| E{✅ Evaluator}
    E -- retry --> P
    E -- pass --> O([🚀 FastAPI → Docker → AWS])

    style P fill:#0d1117,stroke:#00ff9c,color:#fff
    style E fill:#0d1117,stroke:#00ff9c,color:#fff
    style O fill:#00ff9c,stroke:#00ff9c,color:#0d1117
```

---

### 🧰 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,fastapi,docker,aws,ts,mysql,git,linux,vscode&perline=12" />
</p>

---

### 🚀 Featured builds

<table>
<tr>
<td width="50%" valign="top">

#### 📊 [Agentic Analytics](https://github.com/ShubhamRSY/Agentic-Analytics)
Ask questions in plain English, get answers from your data. AI agents that plan, query, and explain analytics.

`Python` `LLMs` `Agents` `Data`

</td>
<td width="50%" valign="top">

#### 🌐 [Portfolio](https://github.com/ShubhamRSY/shubham.portfolio)
Projects, skills and experience in one place.

`Web` `Portfolio`

</td>
</tr>
</table>

<details>
<summary><b>🔭 What's in my lab right now (click to expand)</b></summary>
<br>

| Status | Experiment |
|:--:|---|
| 🟢 | Multi-agent orchestration with tool calling |
| 🟡 | Building custom MCP servers for data sources |
| 🟡 | Evaluating LLM outputs with automated judges |
| ⚪ | Next idea loading... |

</details>

---

### 📡 Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ShubhamRSY&theme=tokyonight&hide_border=true&background=0d1117&ring=00ff9c&fire=00ff9c&currStreakLabel=00ff9c" width="70%"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ShubhamRSY&bg_color=0d1117&color=00ff9c&line=00ff9c&point=ffffff&area=true&area_color=00ff9c&hide_border=true&custom_title=commit%20signal" width="100%"/>
</p>

---

<p align="center">
  <code>&gt; agent.status → open to collaborate on AI, agents & data projects</code>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff9c,100:0d1117&height=100&section=footer" width="100%"/>
</p>
