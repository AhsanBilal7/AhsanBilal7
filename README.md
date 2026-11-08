<!--
  Ahsan Bilal — GitHub Profile README
  Design 1 / 6 — "Signal" (minimal research-professional, green accent — matches design-retro.md) — LIVE
  Alternate designs live in /designs — see designs/README.md for the index.
  Publication data synced with CV/phd_ahsan_ai_single_column.tex and ahsanbilal7.github.io (Nov 2026).
  Note: generated SVG badges must never receive a raw "&" in text-bearing params
  (desc=/lines=/text=) — some services don't XML-escape it, corrupting the SVG. Use "·" instead.
-->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=15803D&height=110&section=header" />

<div align="center">

# Ahsan Bilal

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=3000&pause=900&color=15803D&center=true&vCenter=true&width=700&height=26&lines=LLM+Reasoning+%C2%B7+Test-Time+Compute;Post-Training+for+Self-Evolving+LLMs;Alignment+%C2%B7+Efficient+Inference+%C2%B7+Agentic+AI)](https://ahsanbilal7.github.io/)

</div>

<table width="100%">
<tr>
<td width="44%" valign="top">

**👋 Who I Am**<br/>
Ph.D. CS, University of Oklahoma (REAL Lab) · Research Collaborator, Stanford AI Lab (SAIL). Advised by [Dr. Hougen](https://www.cs.ou.edu/~hougen/resume.html), [Prof. Cioffi](https://cioffi-group.stanford.edu/) & [Dr. Fox](https://emilybfox.su.domains/). Prior: ML Engineer @ Cowlar (YC'17) · B.E. EE, NUST-SEECS.

</td>
<td width="56%" valign="top">

**🧭 Research Interests**<br/>
🧠 LLM Reasoning &nbsp;·&nbsp; ⚡ Test-Time Compute &nbsp;·&nbsp; 🔁 Self-Evolving LLMs &nbsp;·&nbsp; 🎯 Post-Training &amp; Alignment &nbsp;·&nbsp; 💾 KV-Cache Inference &nbsp;·&nbsp; 🤖 Agentic AI
<br/>
**📍 Publishes In**<br/>
![](https://img.shields.io/badge/ICML-15803D?style=flat-square) ![](https://img.shields.io/badge/NeurIPS-15803D?style=flat-square) ![](https://img.shields.io/badge/KDD-15803D?style=flat-square) ![](https://img.shields.io/badge/CoNLL-15803D?style=flat-square) ![](https://img.shields.io/badge/EMNLP-15803D?style=flat-square) ![](https://img.shields.io/badge/TMLR-15803D?style=flat-square) ![](https://img.shields.io/badge/AAAI-15803D?style=flat-square) ![](https://img.shields.io/badge/IEEE%20Network-15803D?style=flat-square) ![](https://img.shields.io/badge/ICASSP-15803D?style=flat-square) ![](https://img.shields.io/badge/ICC-15803D?style=flat-square)

</td>
</tr>
</table>

<div align="center">

🔭 **Now:** Post-training for self-evolving LLMs (minimax-regret self-play) &nbsp;·&nbsp; KV-cache eviction `ICLR'27` &nbsp;·&nbsp; Adaptive test-time compute `ICML'26` &nbsp;·&nbsp; <sub>[full details ↓](#-current-work)</sub>

<p>
<a href="mailto:ahsan.bilal-1@ou.edu"><img src="https://img.shields.io/badge/Email-15803D?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://ahsanbilal7.github.io/"><img src="https://img.shields.io/badge/Website-15803D?style=flat-square&logo=googlechrome&logoColor=white" /></a>
<a href="https://scholar.google.com/citations?user=UxYCwTcAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-15803D?style=flat-square&logo=googlescholar&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/AhsanBilal7"><img src="https://img.shields.io/badge/LinkedIn-15803D?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/AhsanBilal7"><img src="https://img.shields.io/badge/GitHub-15803D?style=flat-square&logo=github&logoColor=white" /></a>
<a href="https://ahsanbilal7.github.io/assets/pdfs/cv.pdf"><img src="https://img.shields.io/badge/CV-15803D?style=flat-square&logo=readdotcv&logoColor=white" /></a>
</p>
<sub><a href="https://x.com/ahsan_bilal7">X</a> · <a href="https://orcid.org/0009-0002-7044-9316">ORCID</a> · <a href="https://www.semanticscholar.org/author/Ahsan-Bilal/2059710534">Semantic Scholar</a> · <a href="https://dblp.org/pid/227/6464.html">DBLP</a></sub>

<sub>
<a href="#-research-focus">Research Focus</a> ·
<a href="#-current-work">Current Work</a> ·
<a href="#-selected-publications">Publications</a> ·
<a href="#-honors">Honors</a> ·
<a href="#-toolbox">Toolbox</a> ·
<a href="#-github-stats">Stats</a>
</sub>

</div>

## 🧭 Research Focus

- 🧠 **Reasoning, Test-Time Compute & RL** — adaptive compute allocation, verifier/PRM-guided and tree search, self-correction, RLVR (PPO/GRPO) for autoregressive & diffusion LMs
- 🔁 **Post-Training for Self-Evolving LLMs** — Challenger–Solver self-play with the designer and solver trained as two independent policies; minimax-regret, PSRO-style environment design over LLM-written verifiable environments; influence-guided RLVR data selection that rewards transferable held-out gain, not difficulty alone
- 🎯 **Alignment, Preference Optimization & AI Safety** — RLHF/DPO, general preference RL, reward decomposition, sycophancy, uncertainty & calibration
- 💾 **Agentic AI & Efficient LLM Systems** — KV-cache eviction/compression/quantization, sparse attention, LLM agents & multi-agent systems, multimodal RAG, AI for wireless (5G+)

## 🚧 Current Work

| Project | Where | Details |
|---|---|---|
| **Post-training for self-evolving LLMs** | REAL Lab, OU | Two-policy Designer–Solver self-play with minimax-regret (PSRO) environment design over verifiable environments; influence-guided RLVR prompt selection tested against realized held-out gains — *ongoing* |
| **Adaptive test-time compute for LLM reasoning** | REAL Lab, OU | Verifier/PRM-guided reasoning, agentic RL controllers, trajectory-level search, self-correction — autoregressive (`ICML'26`, `EMNLP'26`) & diffusion (`ICLR'27`) language models |
| **Memory-efficient LLM inference** | REAL Lab, OU | Monte Carlo future-query estimation for KV-cache eviction, head-adaptive sparse attention (`ICLR'27`), KV-cache quantization faithfulness in RAG (`EMNLP'26 Workshop`) |
| **LLM alignment & preference optimization** | Stanford AI Lab | General preference RL (`ICLR'27`), sycophancy disentanglement via reward decomposition (`COLM'26`) |
| **Diffusion-based wireless estimation & nGRF** | Stanford AI Lab | Neural Gaussian Radio Fields + verifier-guided trajectory search for diffusion test-time scaling in channel prediction (`KDD'26`) |
| **Internet of Agents Platform** | Conoid.ai | Decentralized, self-evolving multi-agent platform — trust/memory-based team formation, secure HTTP agent-communication protocol |
| **Meta-thinking in LLM agents (survey)** | Independent | Survey on meta-thinking via multi-agent reinforcement learning — `EAAI` (under review) |

## 🤝 Contributions

- **Program Committee:** AAAI'27 · VTC2027-Spring (TPC, AI/ML for Communications)
- **Peer Review:** ICLR · ICML · NeurIPS · ICASSP · PAKDD · TMLR · IEEE WCM · Springer MT&A · IP&M · IEEE Access
- **Cross-org research:** co-authored work with researchers from **Google DeepMind** and **Meta AI** (`TMLR'26`), alongside Stanford Statistics, University of Glasgow, and NUST-SEECS
- **Teaching:** Teaching Assistant, *CS-1313: Programming for Non-Majors in C*, University of Oklahoma (Fall 2024–Present)
- **Talks:** *"AI in Healthcare"* — Norman Regional Hospital, with Dr. Lubna Mirza

## 📚 Selected Publications

<sub>30 papers below (22 primary + 8 in "Additional Work"). <sub>\*equal contribution</sub>. Complete, live-updated list → <a href="https://scholar.google.com/citations?user=UxYCwTcAAAAJ">Google Scholar ↗</a></sub>

### LLM Reasoning, Post-Training, Alignment & Efficient Inference

| Publication | Venue |
|---|:---:|
| **[What If We Allocate Test-Time Compute Adaptively?](https://arxiv.org/pdf/2602.01070)**<br/><sub>**A. Bilal**\*, [M.A. Mohsin](https://ahmd-mohsin.github.io/)\*, [M. Umer](https://muhd-umer.github.io/), [A. Subhan](https://alisubhan5341.github.io/), [H. Rizwan](https://scholar.google.com/citations?user=yUCtuKQAAAAJ&hl=en), A. Mohsin, [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html)</sub> | ![ICML](https://img.shields.io/badge/ICML-2026-15803D?style=for-the-badge) |
| **[Monte Carlo Estimation for KV Cache Eviction](https://arxiv.org/pdf/2610.07643)**<br/><sub>**A. Bilal**, [M.A. Mohsin](https://ahmd-mohsin.github.io/), [M. Umer](https://muhd-umer.github.io/), W.H. Raza, [A.U. Asad](https://attaulasad.github.io/), [Y.D. Kwon](https://theyoungkwon.github.io/), [M. Valko](https://misovalko.github.io/), [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html)</sub> | ![ICLR](https://img.shields.io/badge/ICLR-2027-15803D?style=for-the-badge)<br/><sub>under review</sub> |
| **Attend at the Right Resolution: Head-Adaptive Sparse Attention via Query–Key Interaction Structure**<br/><sub>W.H. Raza, **A. Bilal**, Y. Shen, R. Hu, X. Fu, Y. Wen</sub> | ![ICLR](https://img.shields.io/badge/ICLR-2027-15803D?style=for-the-badge)<br/><sub>under review</sub> |
| **[S³: Stratified Scaling Search for Test-Time in Diffusion LMs](https://arxiv.org/pdf/2604.06260)**<br/><sub>**A. Bilal**\*, [M.A. Mohsin](https://ahmd-mohsin.github.io/)\*, [M. Umer](https://muhd-umer.github.io/), [A. Aali](https://asadaali.com/), M.U. Khanzada, M.U. Rafique, Z. He, [E. Fox](https://emilybfox.su.domains/), [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html)</sub> | ![ICLR](https://img.shields.io/badge/ICLR-2027-15803D?style=for-the-badge)<br/><sub>under review</sub> |
| **[General Preference Reinforcement Learning](https://arxiv.org/pdf/2605.18721)**<br/><sub>[M. Umer](https://muhd-umer.github.io/), [M.A. Mohsin](https://ahmd-mohsin.github.io/), **A. Bilal**, [A. Chaudhry](https://arslan-chaudhry.github.io/), A. Haupt, S. Koyejo, [E. Fox](https://emilybfox.su.domains/), [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | ![ICLR](https://img.shields.io/badge/ICLR-2027-15803D?style=for-the-badge)<br/><sub>under review</sub> |
| **[Epistemic Uncertainty for Test-Time Discovery](https://arxiv.org/pdf/2605.11328)**<br/><sub>K. Riaz, [M.A. Mohsin](https://ahmd-mohsin.github.io/), **A. Bilal**, [M. Umer](https://muhd-umer.github.io/), A. Mohsin, A. Riaz, [A. Subhan](https://alisubhan5341.github.io/), [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | ![ICLR](https://img.shields.io/badge/ICLR-2027-15803D?style=for-the-badge)<br/><sub>under review</sub> |
| **[On the Fundamental Limits of LLMs at Scale](https://arxiv.org/pdf/2511.12869)**<br/><sub>[M.A. Mohsin](https://ahmd-mohsin.github.io/), [M. Umer](https://muhd-umer.github.io/), **A. Bilal**, Z. Memon, M.I. Qadir, [S. Bhattacharya](https://scholar.google.com/citations?user=xNb5T5IAAAAJ&hl=en), [H. Rizwan](https://scholar.google.com/citations?user=yUCtuKQAAAAJ&hl=en), A.R. Gorle, M.Z. Kazmi, A. Mohsin, [A. Subhan](https://alisubhan5341.github.io/), M.U. Rafique, Z. He, P. Mehta, J. Han, [M.A. Jamshed](https://scholar.google.com/citations?user=at4MvYMAAAAJ&hl=en), [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html), [J.M. Cioffi](https://cioffi-group.stanford.edu/) · *incl. researchers from Google DeepMind & Meta AI*</sub> | ![TMLR](https://img.shields.io/badge/TMLR-2026-15803D?style=for-the-badge) |
| **[Faithfulness Is Not Free: Auditing Offline KV-Cache Quantization in RAG](https://arxiv.org/pdf/2608.30996)**<br/><sub>[A.U. Asad](https://attaulasad.github.io/)\*, **A. Bilal**\*, M. Ali, M. Haseeb, [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html)</sub> | ![EMNLP](https://img.shields.io/badge/EMNLP-2026-15803D?style=for-the-badge)<br/><sub>Workshop</sub> |
| **[Refining Over Resampling: Test-Time Self-Correction for LLM Reasoning](https://arxiv.org/pdf/2608.05643)**<br/><sub>**A. Bilal**, [M.A. Mohsin](https://ahmd-mohsin.github.io/), [M. Umer](https://muhd-umer.github.io/), L. Trigg, [A. Subhan](https://alisubhan5341.github.io/), M. Ali, [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html)</sub> | ![EMNLP](https://img.shields.io/badge/EMNLP-2026-15803D?style=for-the-badge)<br/><sub>under review</sub> |
| **[Pressure, What Pressure? Sycophancy Disentanglement via Reward Decomposition](https://arxiv.org/pdf/2604.05279)**<br/><sub>[M.A. Mohsin](https://ahmd-mohsin.github.io/)\*, **A. Bilal**\*, [M. Umer](https://muhd-umer.github.io/), [E. Fox](https://emilybfox.su.domains/)</sub> | ![COLM](https://img.shields.io/badge/COLM-2026-15803D?style=for-the-badge)<br/><sub>under review</sub> |
| **[Logic-Level Evaluation of Logical Table-to-Text Generation](https://aclanthology.org/2026.conll-main.41.pdf)**<br/><sub>L. Trigg, [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html), **A. Bilal**</sub> | ![CoNLL](https://img.shields.io/badge/CoNLL-2026-15803D?style=for-the-badge) |
| **[ITDPDM: Information-Theoretic Discrete Poisson Diffusion Model](https://arxiv.org/pdf/2505.05082)**<br/><sub>[S. Bhattacharya](https://scholar.google.com/citations?user=xNb5T5IAAAAJ&hl=en), A.R. Gorle, **A. Bilal**, C. Ding, A.K.S. Yadav, [T. Weissman](https://web.stanford.edu/~tsachy/)</sub> | ![NeurIPS](https://img.shields.io/badge/NeurIPS-2025-15803D?style=for-the-badge) |

### Wireless, Signal & Generative ML

| Publication | Venue |
|---|:---:|
| **Agentic Continual Adaptation: Enabling Lifelong Learning in Wireless Channel Estimation**<br/><sub>**A. Bilal**, [M.A. Mohsin](https://ahmd-mohsin.github.io/), [M. Umer](https://muhd-umer.github.io/), [M.A. Jamshed](https://scholar.google.com/citations?user=at4MvYMAAAAJ&hl=en), A. Mohsin, [J.M. Cioffi](https://cioffi-group.stanford.edu/), [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html)</sub> | ![IEEE Network](https://img.shields.io/badge/IEEE%20Network-2026-15803D?style=for-the-badge) |
| **[Neural Gaussian Radio Fields for Channel Estimation](https://arxiv.org/pdf/2508.11668)**<br/><sub>[M. Umer](https://muhd-umer.github.io/)\*, [M.A. Mohsin](https://ahmd-mohsin.github.io/)\*, **A. Bilal**\*, [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | <a href="https://kdd2026.kdd.org/"><img src="https://img.shields.io/badge/KDD-2026-15803D?style=for-the-badge" /></a> |
| **[Channel Prediction Under Distribution Shift via Continual Learning Regularization](https://arxiv.org/pdf/2509.15192)**<br/><sub>[M.A. Mohsin](https://ahmd-mohsin.github.io/), [M. Umer](https://muhd-umer.github.io/), **A. Bilal**, M.I. Qadir, [M.A. Jamshed](https://scholar.google.com/citations?user=at4MvYMAAAAJ&hl=en), [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html), [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | ![ICASSP](https://img.shields.io/badge/ICASSP-2026-15803D?style=for-the-badge) |
| **[Conditional Prior-Based Non-Stationary Channel Estimation via Accelerated Diffusion](https://arxiv.org/pdf/2509.15182)**<br/><sub>[M.A. Mohsin](https://ahmd-mohsin.github.io/)\*, **A. Bilal**\*, [M. Umer](https://muhd-umer.github.io/), [A. Aali](https://asadaali.com/), [M.A. Jamshed](https://scholar.google.com/citations?user=at4MvYMAAAAJ&hl=en), [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html), [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | ![ICASSP](https://img.shields.io/badge/ICASSP-2026-15803D?style=for-the-badge) |
| **[Transformer-Based Sparse CSI Estimation for Non-Stationary Channels](https://arxiv.org/pdf/2511.01333)**<br/><sub>[M.A. Mohsin](https://ahmd-mohsin.github.io/), [M. Umer](https://muhd-umer.github.io/), **A. Bilal**, [H. Rizwan](https://scholar.google.com/citations?user=yUCtuKQAAAAJ&hl=en), [S. Bhattacharya](https://scholar.google.com/citations?user=xNb5T5IAAAAJ&hl=en), [M.A. Jamshed](https://scholar.google.com/citations?user=at4MvYMAAAAJ&hl=en), [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | ![ICC](https://img.shields.io/badge/ICC-2026-15803D?style=for-the-badge) |
| **Canonical Optimization for MIMO MAC Design**<br/><sub>[M. Umer](https://muhd-umer.github.io/), [M.A. Mohsin](https://ahmd-mohsin.github.io/), **A. Bilal**, [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | ![GLOBECOM](https://img.shields.io/badge/GLOBECOM-2026-15803D?style=for-the-badge) |
| **[RAG with Multi-Modal LLMs for Wireless Environments](https://arxiv.org/pdf/2503.07670)** · [site](https://cioffi-group-stanford.github.io/Websites/RAG_wireless.html)<br/><sub>[M.A. Mohsin](https://ahmd-mohsin.github.io/), **A. Bilal**, [S. Bhattacharya](https://scholar.google.com/citations?user=xNb5T5IAAAAJ&hl=en), [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | ![ICC](https://img.shields.io/badge/ICC-2025-15803D?style=for-the-badge)<br/><sub>🏆 Best Paper</sub> |
| **Continual Learning for Wireless Channel Prediction** · [site](https://cioffi-group-stanford.github.io/Websites/wireless_continual)<br/><sub>[M.A. Mohsin](https://ahmd-mohsin.github.io/), [M. Umer](https://muhd-umer.github.io/), **A. Bilal**, [M.A. Jamshed](https://scholar.google.com/citations?user=at4MvYMAAAAJ&hl=en), [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | ![ICML](https://img.shields.io/badge/ICML-2025-15803D?style=for-the-badge)<br/><sub>Workshop</sub> |
| **[Task and Perception-aware Distributed Source Coding for Correlated Speech](https://arxiv.org/pdf/2501.17879)** · [site](https://cioffi-group-stanford.github.io/Websites/task_aware)<br/><sub>[S. Bhattacharya](https://scholar.google.com/citations?user=xNb5T5IAAAAJ&hl=en), [M.A. Mohsin](https://ahmd-mohsin.github.io/), **A. Bilal**, [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | ![AAAI](https://img.shields.io/badge/AAAI-2025-15803D?style=for-the-badge)<br/><sub>Workshop</sub> |
| **[Hierarchical DRL for Spectrum Resource Optimization in Terrestrial/Non-Terrestrial Networks](https://arxiv.org/pdf/2501.09212)** · [site](https://cioffi-group-stanford.github.io/Websites/hierarchical_wireless.html)<br/><sub>[M.A. Mohsin](https://ahmd-mohsin.github.io/), [H. Rizwan](https://scholar.google.com/citations?user=yUCtuKQAAAAJ&hl=en), [M. Umer](https://muhd-umer.github.io/), [S. Bhattacharya](https://scholar.google.com/citations?user=xNb5T5IAAAAJ&hl=en), **A. Bilal**, [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub> | ![AAAI](https://img.shields.io/badge/AAAI-2025-15803D?style=for-the-badge)<br/><sub>Workshop</sub> |

<details>
<summary><strong>Additional & early-career work</strong> <sub>(8 more — click to expand)</sub></summary><br/>

- **[AgentPersonaBench: Benchmarking Persona-Driven User Simulation](https://arxiv.org/pdf/2610.04379v1)** · [code](https://github.com/MatrAIx-ai/AgentPersonaBench) — `arXiv'26` · open-source contribution to [MatrAIx.ai](https://github.com/MatrAIx-ai)<br/><sub>J. Huang, Y. Wang, H. Shen, …, **A. Bilal**, et al. (46 authors)</sub>
- **[Adaptive Replay Refinement: Allocating Test-Time Compute Between Revision and Resampling](https://arxiv.org/pdf/2610.28294)** — `arXiv'26`<br/><sub>**A. Bilal**, [M.A. Mohsin](https://ahmd-mohsin.github.io/), [M. Umer](https://muhd-umer.github.io/), A. Mohsin, S. Bilal, [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html)</sub>
- **[Meta-Thinking in LLMs via Multi-Agent RL: A Survey](https://arxiv.org/pdf/2504.14520)** · [site](https://cioffi-group-stanford.github.io/Websites/meta_thinking_llms.html) — `EAAI` (under review)<br/><sub>**A. Bilal**, [M.A. Mohsin](https://ahmd-mohsin.github.io/), [M. Umer](https://muhd-umer.github.io/), M.A.K. Bangash, [M.A. Jamshed](https://scholar.google.com/citations?user=at4MvYMAAAAJ&hl=en)</sub>
- **[6G Twin: Hybrid Gaussian Radio Fields for Channel Estimation and Non-Linear Precoder Design](https://arxiv.org/pdf/2509.18735)** — `arXiv'25`<br/><sub>[M.A. Mohsin](https://ahmd-mohsin.github.io/), [M. Umer](https://muhd-umer.github.io/), **A. Bilal**, [M.A. Jamshed](https://scholar.google.com/citations?user=at4MvYMAAAAJ&hl=en), [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html), [J.M. Cioffi](https://cioffi-group.stanford.edu/)</sub>
- **[LLMs for Explainable AI: A Comprehensive Survey](https://arxiv.org/pdf/2504.00125)** — `arXiv'25`<br/><sub>**A. Bilal**, D. Ebert, [B. Lin](https://beiyulincs.github.io/)</sub>
- **Abstract — LLM for Explainable AI** — `IEEE DSAA'24` (Poster)<br/><sub>**A. Bilal**, [B. Lin](https://beiyulincs.github.io/)</sub>
- **On Shadow Removal With Boosted Attention in a Vision Transformer** — `Springer ML` (under review)<br/><sub>**A. Bilal**, [A. Salman](https://seecs.nust.edu.pk/faculty/ahmad-salman/), [K. Khurshid](https://namal.edu.pk/faculty/profile/150/dr-khawar-khurshid), [D.F. Hougen](https://www.cs.ou.edu/~hougen/resume.html)</sub>
- **Person Identification using Gait with Fused Graph & 3D-CNN** — `ACM TAIS` (under review)<br/><sub>**A. Bilal**, [A. Salman](https://seecs.nust.edu.pk/faculty/ahmad-salman/), [K. Khurshid](https://namal.edu.pk/faculty/profile/150/dr-khawar-khurshid)</sub>

</details>

## 🏆 Honors

- 🥈 **Silver Reviewer Award** — ICML 2026
- 🎓 **Gallogly College of Engineering Graduate Fellowship** — 2025
- 🥇 **Best Paper Award** — ICC Workshop 2025, Montreal
- 📜 **Honorary Certificate of Appreciation** — IEEE ComSoc Student Competition 2025 *(Democratizing 6G)*
- 🥈 **Best Student Presentation Runner-up** — IEEE DSAA'24 Student Forum
- ✈️ **Student Travel Grant** — IEEE DSAA 2024, San Diego
- 🌍 **UGRIP Selection** — MBZUAI, First Cohort
- 🇵🇰 **IEEE Emerging Young Researcher** — IEEE Islamabad Section

## 🧰 Toolbox

<p align="center">
<img src="https://skillicons.dev/icons?i=py,anaconda,latex,cpp,c,java,matlab,pytorch,tensorflow,opencv,sklearn&theme=dark" alt="Languages, ML & DL" />
<br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,git,github,linux,vscode,aws,nginx,raspberrypi,react,nextjs,js,html,css&theme=dark" alt="Infra, MLOps & Web" />
<br/>
<img src="https://skillicons.dev/icons?i=figma,xd,ai,ps,wordpress&theme=dark" alt="Design" />
</p>


<p align="center"><sub><strong>ML Techniques:</strong> GRPO · LoRA · ZeRO · Preference Optimization · Test-Time Scaling · LLM Post-Training · Agentic Systems</sub></p>
<p align="center"><sub><strong>Also:</strong> Statistical Learning Theory · Probabilistic Modelling · Information Theory · Optimization · MLflow · CUDA · Slurm · Cursor · Pandas/NumPy · Signal Processing · 5G · Connectivity Technologies · Distributed AI Systems · Classification · Algorithms</sub></p>

## 📊 GitHub Stats

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=AhsanBilal7&show_icons=true&hide_border=true&bg_color=0D1117&title_color=39FF14&icon_color=39FF14&text_color=c9d1d9" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=AhsanBilal7&show_icons=true&hide_border=true&bg_color=ffffff&title_color=15803D&icon_color=15803D&text_color=24292f" />
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=AhsanBilal7&show_icons=true&hide_border=true&bg_color=ffffff&title_color=15803D&icon_color=15803D&text_color=24292f" alt="Ahsan's GitHub Stats" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=AhsanBilal7&layout=compact&hide_border=true&bg_color=0D1117&title_color=39FF14&text_color=c9d1d9" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=AhsanBilal7&layout=compact&hide_border=true&bg_color=ffffff&title_color=15803D&text_color=24292f" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AhsanBilal7&layout=compact&hide_border=true&bg_color=ffffff&title_color=15803D&text_color=24292f" alt="Top Languages" />
</picture>
</p>
<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=AhsanBilal7&hide_border=true&background=0D1117&ring=39FF14&fire=39FF14&currStreakLabel=39FF14&sideLabels=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=8b949e" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=AhsanBilal7&hide_border=true&background=ffffff&ring=15803D&fire=15803D&currStreakLabel=15803D&sideLabels=24292f&currStreakNum=24292f&sideNums=24292f&dates=57606a" />
  <img src="https://streak-stats.demolab.com?user=AhsanBilal7&hide_border=true&background=ffffff&ring=15803D&fire=15803D&currStreakLabel=15803D" alt="GitHub Streak" />
</picture>
</p>
<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=AhsanBilal7&bg_color=0D1117&color=39FF14&line=39FF14&point=c9d1d9&hide_border=true&area=true&custom_title=Contribution%20Activity" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=AhsanBilal7&bg_color=ffffff&color=15803D&line=15803D&point=0B0F0C&hide_border=true&area=true&custom_title=Contribution%20Activity" />
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=AhsanBilal7&bg_color=ffffff&color=15803D&line=15803D&point=0B0F0C&hide_border=true&area=true&custom_title=Contribution%20Activity" alt="Contribution Activity Graph" />
</picture>
</p>

<div align="center">
<img src="https://komarev.com/ghpvc/?username=AhsanBilal7&color=15803D&style=flat-square&label=Profile+Views" />
<br/><sub>Open to research collaborations in LLM reasoning, post-training for self-evolving LLMs, efficient inference, and agentic AI. Reach out via <a href="mailto:ahsan.bilal-1@ou.edu">email</a> or <a href="https://www.linkedin.com/in/AhsanBilal7">LinkedIn</a>.</sub>

<!-- Other visual designs of this profile: see /designs (design-terminal.md, design-cards.md) -->

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=15803D&height=120&section=footer" />
