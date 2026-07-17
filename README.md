<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=220&color=0:0F172A,48:1E293B,100:334155&text=yongh&fontColor=F8FAFC&fontSize=54&fontAlignY=42&desc=Software%20Engineering%20%C2%B7%20AI%20Systems%20%C2%B7%20Research%20Engineering&descAlignY=63&descSize=17&animation=fadeIn" />

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=400&size=18&duration=3400&pause=1200&color=64748B&center=true&vCenter=true&repeat=true&width=900&height=42&lines=Building+reliable+AI+systems+from+models+to+products;%E5%B0%86%E6%A8%A1%E5%9E%8B%E8%83%BD%E5%8A%9B%E8%BD%AC%E5%8C%96%E4%B8%BA%E5%8F%AF%E7%94%A8%E3%80%81%E5%8F%AF%E9%9D%A0%E7%9A%84%E6%99%BA%E8%83%BD%E7%B3%BB%E7%BB%9F" alt="Typing introduction" />

<br/>

<a href="https://github.com/telitor/SciPilot"><img src="https://img.shields.io/badge/Featured-SciPilot-334155?style=flat-square&logo=github&logoColor=white" /></a>
<img src="https://img.shields.io/badge/DUT-Software%20Engineering-475569?style=flat-square" />
<img src="https://img.shields.io/badge/MCM%2FICM-M%20Award-64748B?style=flat-square" />

<br/><br/>

[**SciPilot**](https://github.com/telitor/SciPilot) · [**Repositories / 项目仓库**](https://github.com/telitor?tab=repositories)

</div>

---

## 01 — Profile / 个人简介

<table>
<tr>
<td width="50%" valign="top">

### English

Software Engineering student at **Dalian University of Technology**, working at the intersection of intelligent systems and software engineering.

I focus on the engineering layer between model capability and real-world use: system architecture, agent orchestration, secure data flows, persistent context, and reproducible workflows.

</td>
<td width="50%" valign="top">

### 中文

大连理工大学软件工程专业学生，关注智能系统与软件工程的交叉实践。

相比只关注模型本身，我更重视模型能力如何被组织、调度、保护与持久化，并最终形成结构清晰、能够稳定运行的完整系统。

</td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="33%" align="center" valign="top">

### AI Systems

Multi-Agent Systems  
Computer Vision  
Multimodal Intelligence

**智能系统 · 视觉 · 多模态**

</td>
<td width="33%" align="center" valign="top">

### System Engineering

Backend Architecture  
Service Boundaries  
Secure Data Flows

**后端架构 · 服务设计 · 数据安全**

</td>
<td width="33%" align="center" valign="top">

### Research Engineering

Reproducible Workflows  
Experiment Analysis  
Research Tooling

**科研工作流 · 实验分析 · 工程工具**

</td>
</tr>
</table>

---

## 02 — Featured Project / 核心项目

### [SciPilot](https://github.com/telitor/SciPilot)

> **Multi-Agent Research Engineering Platform / 多智能体科研工程平台**

<table>
<tr>
<td width="58%" valign="top">

SciPilot connects five specialized agents into one coherent research workflow, covering paper reading, problem decomposition, result interpretation, code reproduction, and project planning.

SciPilot 将五类垂直智能体接入统一系统，覆盖论文精读、问题拆解、结果分析、代码复现与项目规划，形成从用户输入到智能处理、结果展示和数据持久化的完整闭环。

**System focus / 系统重点**

- Unified FastAPI gateway / 统一后端网关
- Category-based agent routing / 基于类别的智能体调度
- Independent WebSocket runtimes / 独立 WebSocket 运行时
- Supabase Auth and RLS / 身份认证与行级权限
- Persistent conversations and messages / 会话与消息持久化

</td>
<td width="42%" valign="top">

### Agent Matrix / 智能体矩阵

`01` Paper Reading / 论文精读  
`02` Problem Decomposition / 问题拆解  
`03` Result Interpretation / 结果分析  
`04` Code Reproduction / 代码复现  
`05` Project Planning / 项目规划

### Core Stack / 核心技术

`React` · `TypeScript`  
`FastAPI` · `Pydantic`  
`Supabase` · `PostgreSQL`  
`WebSocket` · `RLS`

[**View repository → / 查看项目 →**](https://github.com/telitor/SciPilot)

</td>
</tr>
</table>

```mermaid
%%{init: {"theme": "neutral", "flowchart": {"curve": "basis"}}}%%
flowchart LR
    U[User Interface<br/>用户界面] --> G[FastAPI Gateway<br/>统一后端网关]
    G --> D{Agent Dispatcher<br/>智能体调度}
    D --> A1[Paper Reading]
    D --> A2[Problem Decomposition]
    D --> A3[Result Interpretation]
    D --> A4[Code Reproduction]
    D --> A5[Project Planning]
    A1 --> P[Supabase Persistence<br/>数据持久化]
    A2 --> P
    A3 --> P
    A4 --> P
    A5 --> P
```

---

## 03 — Selected Work / 代表项目

<table>
<tr>
<td width="33%" valign="top">

### [Digit Recognition CNN](https://github.com/telitor/digit-recognition-cnn)

CNN-based handwritten digit recognition with model training, evaluation, and visualized inference.

基于卷积神经网络的手写数字识别项目，覆盖模型训练、性能评估与推理结果可视化。

`Python` · `PyTorch` · `OpenCV`

</td>
<td width="33%" valign="top">

### [Robot Path Planning](https://github.com/telitor/robot-path-planning)

A* path planning with map parsing, obstacle avoidance, path reconstruction, and visualization.

基于 A* 搜索的路径规划项目，实现地图解析、障碍规避、路径回溯与规划结果可视化。

`Python` · `A* Search` · `Visualization`

</td>
<td width="33%" valign="top">

### [Housing Regression](https://github.com/telitor/california-housing-regression)

Regression experiments with preprocessing, model comparison, metric evaluation, and ablation analysis.

围绕数据预处理、模型对比、评价指标与消融分析构建的机器学习回归实验。

`Python` · `scikit-learn` · `Regression`

</td>
</tr>
</table>

---

## 04 — Technical Scope / 技术能力

| Domain / 方向 | Technologies & Practices / 技术与实践 |
|---|---|
| **Agent Systems / 智能体系统** | Agent routing, independent runtime configuration, signed WebSocket communication, structured responses |
| **Backend Engineering / 后端工程** | FastAPI, Pydantic, REST APIs, authentication, service-layer design |
| **Data & Security / 数据与安全** | Supabase, PostgreSQL, Row Level Security, conversation persistence |
| **Frontend Engineering / 前端工程** | React, TypeScript, Vite, Tailwind CSS, Zustand, Axios |
| **Machine Learning / 机器学习** | PyTorch, scikit-learn, CNN, model evaluation, experiment analysis |
| **Engineering Workflow / 工程流程** | Git, GitHub, environment isolation, API documentation, reproducible setup |

<br/>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,fastapi,react,ts,vite,tailwind,supabase,postgres,git,github&theme=light" alt="Core technology stack" />

</div>

---

## 05 — Engineering Direction / 当前方向

```mermaid
%%{init: {"theme": "neutral", "flowchart": {"curve": "linear"}}}%%
flowchart LR
    M[Model Capability<br/>模型能力] --> S[System Architecture<br/>系统架构]
    S --> O[Agent Orchestration<br/>智能体编排]
    O --> W[Research Workflow<br/>科研工作流]
    W --> P[Usable Product<br/>可用产品]
```

<table>
<tr>
<td width="50%" valign="top">

### Current Focus

- Multi-agent orchestration
- Research workflow automation
- Reliable AI application architecture
- Computer vision and multimodal systems

</td>
<td width="50%" valign="top">

### 当前关注

- 多智能体调度与协作
- 科研工作流自动化
- 可靠的 AI 应用架构
- 计算机视觉与多模态系统

</td>
</tr>
</table>

---

## 06 — Recognition / 经历

<table>
<tr>
<td width="50%" align="center">

### Dalian University of Technology

Software Engineering  
**大连理工大学 · 软件工程**

</td>
<td width="50%" align="center">

### MCM / ICM

Meritorious Winner  
**美国大学生数学建模竞赛 M 奖**

</td>
</tr>
</table>

---

<div align="center">

### From model capability to usable systems.

**让模型能力真正进入系统，并成为可以使用的产品。**

<br/>

[**Explore SciPilot / 查看 SciPilot**](https://github.com/telitor/SciPilot) · [**View All Repositories / 浏览全部项目**](https://github.com/telitor?tab=repositories)

<br/>

<sub>Software Engineering · Artificial Intelligence · Research Systems</sub>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=50&color=0:334155,50:1E293B,100:0F172A&section=footer" />

</div>
