# Hi, I'm Zhilun Hu (胡至伦) 👋

<p align="left">
  <a href="https://hzl666.xyz/"><img src="https://img.shields.io/badge/Academic_Homepage-hzl666.xyz-0f766e?style=flat-square&logo=google-scholar" alt="Academic Homepage"/></a>
  <a href="https://github.com/169884902hzl/Towards-Practical-Embodied-Intelligence"><img src="https://img.shields.io/badge/Flagship_Survey_&_Textbook-Towards_Practical_Embodied_Intelligence-2563eb?style=flat-square&logo=github" alt="Towards Practical Embodied Intelligence"/></a>
  <a href="https://169884902hzl.github.io/Towards-Practical-Embodied-Intelligence/"><img src="https://img.shields.io/badge/Interactive_Workbench-GitHub_Pages-0284c7?style=flat-square&logo=googlechrome" alt="Live Interactive Workbench"/></a>
  <a href="https://github.com/169884902hzl/local-domain-expert-vault"><img src="https://img.shields.io/badge/Research_Governance_Vault-local--domain--expert--vault-059669?style=flat-square&logo=obsidian" alt="Local Domain Expert Vault"/></a>
  <img src="https://img.shields.io/badge/Affiliation-HUST-b91c1c?style=flat-square" alt="HUST"/>
</p>

> **Research Focus**: **Embodied Intelligence (EI)** · **Vision-Language-Action (VLA) & World Action Models (WAM)** · **Online Reinforcement Learning for Flow/Diffusion Policies** · **Visuotactile & Contact-Rich Manipulation** · **Bimanual Deformable Linear Objects (DLO / Cable Routing)** · **Real-Time Asynchronous Execution (`RTC`) & Closed-Loop Verification**
>
> **研究方向（华中科技大学 HUST）**：**具身智能与机器人操作** · **VLA 视觉-语言-动作大模型与世界动作模型 (WAM)** · **流匹配/扩散策略强化学习后训练** · **视触觉感知与富接触装配** · **双臂柔性线缆 (DLO) 操作** · **本地优先的多智能体科研治理系统**

---

## 🚀 Flagship Open-Source Ecosystem (双核开源体系)

My open-source work forms a closed loop between **automated local-first literature governance (`local-domain-expert-vault`)** and **rigorous, textbook-grade embodied intelligence synthesis & code verification (`Towards-Practical-Embodied-Intelligence`)**:

| Repository | Positioning & Core Deliverables | Quick Entry Points |
|:---|:---|:---|
| 🌟 **[`Towards-Practical-Embodied-Intelligence`](https://github.com/169884902hzl/Towards-Practical-Embodied-Intelligence)** | **Bilingual Survey + Modular Tutorial + 44 Teaching Figures (25 SVG + 19 JPG) + 5 Synthetic Labs**<br>• 7 research tracks, a 60-paper reading list, and 17 dataset/simulator/benchmark entries<br>• Control, generative policies, RTC and statistical evaluation with explicit evidence boundaries | [📖 English Survey](https://github.com/169884902hzl/Towards-Practical-Embodied-Intelligence/blob/main/README.md)<br>[📘 中文综述与教材导航](https://github.com/169884902hzl/Towards-Practical-Embodied-Intelligence/blob/main/README_zh.md)<br>[🌐 **Live HTML Workbench**](https://169884902hzl.github.io/Towards-Practical-Embodied-Intelligence/)<br>[💻 5 PyTorch Code Labs](https://github.com/169884902hzl/Towards-Practical-Embodied-Intelligence/tree/main/labs) |
| 🧠 **[`local-domain-expert-vault`](https://github.com/169884902hzl/local-domain-expert-vault)** | **v1.0 Local-First Research Governance Workbench (Obsidian + Zotero + Multi-Agent Pipeline)**<br>• Turns a local Zotero + Obsidian corpus (**1,186 public paper-index entries**, `wiki/topics/`, `wiki/concepts/`, `wiki/entities/`) into an auditable domain expert<br>• Transactional state machine: `arXiv OAI-PMH Mirror` $\to$ `Claudian Deep Reading` $\to$ `Paper Primitives & Claim Graph` $\to$ `Gemini Candidates` $\to$ `DeepSeek Scientific Critique` $\to$ `Codex Execution Audit` $\to$ `Human Governance Gate` | [📘 中文主页](https://github.com/169884902hzl/local-domain-expert-vault/blob/main/README.md)<br>[📖 English README](https://github.com/169884902hzl/local-domain-expert-vault/blob/main/README_EN.md)<br>[🏆 Top-60 Paper Canon](https://github.com/169884902hzl/Towards-Practical-Embodied-Intelligence/blob/main/docs/00_Must_Read_60_Leaderboard.md) |

<p align="center">
  <a href="https://github.com/169884902hzl/Towards-Practical-Embodied-Intelligence">
    <img src="https://raw.githubusercontent.com/169884902hzl/Towards-Practical-Embodied-Intelligence/main/assets/ei_tutorial/hero_closed_loop.svg" width="96%" alt="Embodied Intelligence Closed-Loop System Overview"/>
  </a>
</p>

---

## 🏅 Selected Publications & Manuscripts (近期学术发表)

- **[2026 · IEEE CASE (Accepted, Paper ThCT6.3)]** [**Active Observation for Robust Visual Servoing in Robotic Manipulation**](https://hzl666.xyz/projects/active-observation/)
  **Zhilun Hu**, Yuqi Cheng, Yuxiang Tan, Wen-pan Li, and Weiming Shen · *2026 IEEE International Conference on Automation Science and Engineering (CASE)*
  [[Official Program (ThCT6.3)](https://ras.papercept.net/conferences/scripts/rtf/CASE26_ContentListWeb_4.html)] [[Project Page](https://hzl666.xyz/projects/active-observation/)] [[Publications](https://hzl666.xyz/publications/)]


---

## 🔬 Technical Highlights & Executable PyTorch Labs

The [five teaching labs](https://github.com/169884902hzl/Towards-Practical-Embodied-Intelligence/tree/main/labs) use **synthetic data, not real results**. They do not reproduce or rank published robot policies.

1. **Lab 1:** check flow-gradient isolation while an auxiliary loss still updates the backbone; measure local runtime.
2. **Lab 2:** demonstrate the paper RTC mask, clipped coefficient and endpoint VJP on a synthetic linear field.
3. **Lab 3:** check a configurable two-stage rollout and matched-network input-dropout ablation; report MSE without an assumed winner.
4. **Lab 4:** verify the joint Gaussian PPO ratio, KL regularization and Bellman TD target; compare derivatives of identical synthetic forward trajectories.
5. **Lab 5:** compute Wilson intervals and exact paired McNemar tests for arbitrary Method A/B/C/D outcomes; no paper-method success rates are implied.

<p align="center">
  <a href="https://github.com/169884902hzl/Towards-Practical-Embodied-Intelligence">
    <img src="https://raw.githubusercontent.com/169884902hzl/Towards-Practical-Embodied-Intelligence/main/assets/ei_tutorial/benchmark_sota_comparison_2026.svg" width="96%" alt="Benchmark protocol comparison guide"/>
  </a>
</p>
