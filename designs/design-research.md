<!--
  Ahsan Bilal — GitHub Profile README
  Design 5 / 6 — "Research" (formal academic / faculty-page style, citation-list publications)
  To use: copy this file's content over the root README.md
-->

<div align="center">

# Ahsan Bilal

</div>

<table width="100%">
<tr>
<td width="44%" valign="top">

**Who I Am**
Ph.D. Researcher, Computer Science, University of Oklahoma (REAL Lab); Research Collaborator, Stanford AI Lab (SAIL). Advised by Dr. Dean Hougen, Prof. John M. Cioffi & Dr. Emily Fox. Prior: ML Engineer, Cowlar Design Studio (YC '17). B.E. EE, NUST-SEECS.

</td>
<td width="56%" valign="top">

**Research Keywords**
<sub>LLM Reasoning · Test-Time Compute · Post-Training for Self-Evolving LLMs · Preference Optimization · Efficient Inference (KV Cache) · Agentic AI</sub>

**Publishes In**
<br/>![](https://img.shields.io/badge/ICML-7A1F3D?style=flat-square) ![](https://img.shields.io/badge/NeurIPS-7A1F3D?style=flat-square) ![](https://img.shields.io/badge/CoNLL-7A1F3D?style=flat-square) ![](https://img.shields.io/badge/KDD-7A1F3D?style=flat-square) ![](https://img.shields.io/badge/TMLR-7A1F3D?style=flat-square) ![](https://img.shields.io/badge/AAAI-7A1F3D?style=flat-square) ![](https://img.shields.io/badge/ICASSP-7A1F3D?style=flat-square) ![](https://img.shields.io/badge/ICC-7A1F3D?style=flat-square)

</td>
</tr>
</table>

<div align="center">

<sub><strong>Now:</strong> post-training for self-evolving LLMs (minimax-regret self-play) · KV-cache eviction (ICLR'27) · adaptive test-time compute (ICML'26) — <a href="#current-work">see Current Work</a></sub>

<img src="https://capsule-render.vercel.app/api?type=rect&color=7A1F3D&height=2&width=760" />

<p>
<a href="mailto:ahsan.bilal-1@ou.edu"><img src="https://img.shields.io/badge/Email-7A1F3D?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://ahsanbilal7.github.io/"><img src="https://img.shields.io/badge/Website-7A1F3D?style=flat-square&logo=googlechrome&logoColor=white" /></a>
<a href="https://scholar.google.com/citations?user=UxYCwTcAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-7A1F3D?style=flat-square&logo=googlescholar&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/AhsanBilal7"><img src="https://img.shields.io/badge/LinkedIn-7A1F3D?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/AhsanBilal7"><img src="https://img.shields.io/badge/GitHub-7A1F3D?style=flat-square&logo=github&logoColor=white" /></a>
<a href="https://ahsanbilal7.github.io/assets/pdfs/cv.pdf"><img src="https://img.shields.io/badge/Curriculum%20Vitae-7A1F3D?style=flat-square&logo=readdotcv&logoColor=white" /></a>
</p>
<sub><a href="https://www.semanticscholar.org/author/Ahsan-Bilal/2059710534">Semantic Scholar</a> · <a href="https://dblp.org/pid/227/6464.html">DBLP</a> · <a href="https://orcid.org/0009-0002-7044-9316">ORCID</a></sub>

<br/>
<sub><a href="#research-focus">Research Focus</a> · <a href="#current-work">Current Work</a> · <a href="#contributions">Contributions</a> · <a href="#publications">Publications</a> · <a href="#honors">Honors</a> · <a href="#toolbox">Toolbox</a> · <a href="#github-stats">Stats</a></sub>

</div>

## Research Focus

Optimization theory and test-time compute for reasoning-oriented large language models — post-training methods, preference optimization, alignment, and verifier/PRM-guided search across autoregressive and diffusion language models. A current focus is post-training for self-evolving LLMs: Challenger–Solver self-play in which an environment designer and a reasoning solver, trained as two independent policies, co-evolve through minimax-regret (PSRO) environment design over LLM-written verifiable environments, together with influence-guided RLVR data selection that rewards tasks for transferable held-out gain rather than difficulty alone. Further lines of work cover memory-efficient inference (KV-cache eviction, compression, and quantization) and alignment and reliability (sycophancy, uncertainty). A parallel line of work designs evolving, self-organizing multi-agent systems with dynamic reputation and trust modelling, and develops reinforcement learning methods for reasoning and non-stationary decision problems, with applications extending to diffusion-based generative modeling for wireless and signal-processing systems.

## Current Work

- **Post-training for self-evolving LLMs** *(REAL Lab, OU)* — Challenger–Solver self-play with minimax-regret (PSRO) environment design over verifiable environments; influence-guided RLVR data selection (ongoing).
- **Memory-efficient LLM inference** *(REAL Lab, OU)* — Monte Carlo KV-cache eviction and head-adaptive sparse attention (ICLR'27), KV-cache quantization faithfulness in RAG (EMNLP'26 Workshop).
- **Adaptive test-time compute for LLM reasoning** *(REAL Lab, OU)* — verifier/PRM-guided reasoning, agentic RL controllers, trajectory-level search across autoregressive (ICML'26) and diffusion (ICLR'27) language models.
- **Diffusion-based wireless estimation & neural Gaussian radio fields** *(Stanford AI Lab)* — verifier-guided trajectory search for diffusion test-time scaling in channel prediction (KDD'26).
- **Internet of Agents platform** *(Conoid.ai)* — a decentralized, self-evolving multi-agent system built on trust/memory-based team formation and a secure HTTP agent-communication protocol.
- **Meta-thinking in LLM agents** *(survey, independent)* — a survey of meta-thinking via multi-agent reinforcement learning (EAAI, under review).

## Contributions

**Program committee** — AAAI'27 · VTC2027-Spring (TPC)
**Peer review** — ICLR, ICML, NeurIPS, ICASSP, PAKDD, TMLR, IEEE WCM, Springer MT&A, IP&M, IEEE Access
**Cross-organization research** — co-authored work with researchers from Google DeepMind and Meta AI (TMLR'26), alongside collaborators at Stanford Statistics, the University of Glasgow, and NUST-SEECS
**Teaching** — Teaching Assistant, *CS-1313: Programming for Non-Majors in C*, University of Oklahoma (Fall 2024–Present)
**Invited talks** — *"AI in Healthcare,"* Norman Regional Hospital, with Dr. Lubna Mirza

## Publications
<sub>Complete, continuously updated list on <a href="https://scholar.google.com/citations?user=UxYCwTcAAAAJ">Google Scholar</a>. \* denotes equal contribution.</sub>

### LLM Reasoning, Post-Training, Alignment & Efficient Inference

1. A. Bilal\*, M.A. Mohsin\*, M. Umer, A. Subhan, H. Rizwan, A. Mohsin, D.F. Hougen. "What If We Allocate Test-Time Compute Adaptively?." **ICML**, 2026. [[PDF]](https://arxiv.org/pdf/2602.01070)
2. A. Bilal, M.A. Mohsin, M. Umer, W.H. Raza, A.U. Asad, Y.D. Kwon, M. Valko, D.F. Hougen. "Monte Carlo Estimation for KV Cache Eviction." **ICLR**, 2027 (under review). [[PDF]](https://arxiv.org/pdf/2610.07643)
3. W.H. Raza, A. Bilal, Y. Shen, R. Hu, X. Fu, Y. Wen. "Attend at the Right Resolution: Head-Adaptive Sparse Attention via Query–Key Interaction Structure." **ICLR**, 2027 (under review).
4. A. Bilal\*, M.A. Mohsin\*, M. Umer, A. Aali, M.U. Khanzada, M.U. Rafique, Z. He, E. Fox, D.F. Hougen. "S³: Stratified Scaling Search for Test-Time in Diffusion LMs." **ICLR**, 2027 (under review). [[PDF]](https://arxiv.org/pdf/2604.06260)
5. M. Umer, M.A. Mohsin, A. Bilal, A. Chaudhry, A. Haupt, S. Koyejo, E. Fox, J.M. Cioffi. "General Preference Reinforcement Learning." **ICLR**, 2027 (under review). [[PDF]](https://arxiv.org/pdf/2605.18721)
6. K. Riaz, M.A. Mohsin, A. Bilal, M. Umer, A. Mohsin, A. Riaz, A. Subhan, J.M. Cioffi. "Epistemic Uncertainty for Test-Time Discovery." **ICLR**, 2027 (under review). [[PDF]](https://arxiv.org/pdf/2605.11328)
7. M.A. Mohsin, M. Umer, A. Bilal, Z. Memon, M.I. Qadir, S. Bhattacharya, H. Rizwan, A.R. Gorle, M.Z. Kazmi, A. Mohsin, A. Subhan, M.U. Rafique, Z. He, P. Mehta, J. Han, M.A. Jamshed, D.F. Hougen, J.M. Cioffi · *incl. researchers from Google DeepMind and Meta AI*. "On the Fundamental Limits of LLMs at Scale." **TMLR**, 2026. [[PDF]](https://arxiv.org/pdf/2511.12869)
8. A.U. Asad\*, A. Bilal\*, M. Ali, M. Haseeb, D.F. Hougen. "Faithfulness Is Not Free: Auditing Offline KV-Cache Quantization in RAG." **EMNLP Workshop**, 2026. [[PDF]](https://arxiv.org/pdf/2608.30996)
9. A. Bilal, M.A. Mohsin, M. Umer, L. Trigg, A. Subhan, M. Ali, D.F. Hougen. "Refining Over Resampling: Test-Time Self-Correction for LLM Reasoning." **EMNLP**, 2026 (under review). [[PDF]](https://arxiv.org/pdf/2608.05643)
10. M.A. Mohsin\*, A. Bilal\*, M. Umer, E. Fox. "Pressure, What Pressure? Sycophancy Disentanglement via Reward Decomposition." **COLM**, 2026 (under review). [[PDF]](https://arxiv.org/pdf/2604.05279)
11. L. Trigg, D.F. Hougen, A. Bilal. "Logic-Level Evaluation of Logical Table-to-Text Generation." **CoNLL**, 2026. [[PDF]](https://aclanthology.org/2026.conll-main.41.pdf)
12. S. Bhattacharya, A.R. Gorle, A. Bilal, C. Ding, A.K.S. Yadav, T. Weissman. "ITDPDM: Information-Theoretic Discrete Poisson Diffusion Model." **NeurIPS**, 2025. [[PDF]](https://arxiv.org/pdf/2505.05082)

### Wireless, Signal & Generative ML

13. A. Bilal, M.A. Mohsin, M. Umer, M.A. Jamshed, A. Mohsin, J.M. Cioffi, D.F. Hougen. "Agentic Continual Adaptation: Enabling Lifelong Learning in Wireless Channel Estimation." **IEEE Network**, 2026.
14. M. Umer\*, M.A. Mohsin\*, A. Bilal\*, J.M. Cioffi. "Neural Gaussian Radio Fields for Channel Estimation." **KDD**, 2026. [[PDF]](https://arxiv.org/pdf/2508.11668)
15. M.A. Mohsin, M. Umer, A. Bilal, M.I. Qadir, M.A. Jamshed, D.F. Hougen, J.M. Cioffi. "Channel Prediction Under Distribution Shift via Continual Learning Regularization." **ICASSP**, 2026. [[PDF]](https://arxiv.org/pdf/2509.15192)
16. M.A. Mohsin\*, A. Bilal\*, M. Umer, A. Aali, M.A. Jamshed, D.F. Hougen, J.M. Cioffi. "Conditional Prior-Based Non-Stationary Channel Estimation via Accelerated Diffusion." **ICASSP**, 2026. [[PDF]](https://arxiv.org/pdf/2509.15182)
17. M.A. Mohsin, M. Umer, A. Bilal, H. Rizwan, S. Bhattacharya, M.A. Jamshed, J.M. Cioffi. "Transformer-Based Sparse CSI Estimation for Non-Stationary Channels." **ICC**, 2026. [[PDF]](https://arxiv.org/pdf/2511.01333)
18. M. Umer, M.A. Mohsin, A. Bilal, J.M. Cioffi. "Canonical Optimization for MIMO MAC Design." **GLOBECOM**, 2026.
19. M.A. Mohsin, A. Bilal, S. Bhattacharya, J.M. Cioffi. "RAG with Multi-Modal LLMs for Wireless Environments." **ICC Workshop**, 2025 — **Best Paper Award**. [[PDF]](https://arxiv.org/pdf/2503.07670) · [[Site]](https://cioffi-group-stanford.github.io/Websites/RAG_wireless.html)
20. M.A. Mohsin, M. Umer, A. Bilal, M.A. Jamshed, J.M. Cioffi. "Continual Learning for Wireless Channel Prediction." **ICML Workshop**, 2025. · [[Site]](https://cioffi-group-stanford.github.io/Websites/wireless_continual)
21. S. Bhattacharya, M.A. Mohsin, A. Bilal, J.M. Cioffi. "Task and Perception-aware Distributed Source Coding for Correlated Speech." **AAAI Workshop**, 2025. [[PDF]](https://arxiv.org/pdf/2501.17879) · [[Site]](https://cioffi-group-stanford.github.io/Websites/task_aware)
22. M.A. Mohsin, H. Rizwan, M. Umer, S. Bhattacharya, A. Bilal, J.M. Cioffi. "Hierarchical DRL for Spectrum Resource Optimization in Terrestrial/Non-Terrestrial Networks." **AAAI Workshop**, 2025. [[PDF]](https://arxiv.org/pdf/2501.09212) · [[Site]](https://cioffi-group-stanford.github.io/Websites/hierarchical_wireless.html)

<details>
<summary><strong>Additional & early-career publications (8)</strong></summary><br/>

23. J. Huang, Y. Wang, H. Shen, A. Bilal, et al. (46 authors). "AgentPersonaBench: Benchmarking Persona-Driven User Simulation." **arXiv**, 2026. [[PDF]](https://arxiv.org/pdf/2610.04379v1)
24. A. Bilal, M.A. Mohsin, M. Umer, A. Mohsin, S. Bilal, D.F. Hougen. "Adaptive Replay Refinement: Allocating Test-Time Compute Between Revision and Resampling." **arXiv**, 2026. [[PDF]](https://arxiv.org/pdf/2610.28294)
25. A. Bilal, M.A. Mohsin, M. Umer, M.A.K. Bangash, M.A. Jamshed. "Meta-Thinking in LLMs via Multi-Agent RL: A Survey." **EAAI** (under review). [[PDF]](https://arxiv.org/pdf/2504.14520) · [[Site]](https://cioffi-group-stanford.github.io/Websites/meta_thinking_llms.html)
26. M.A. Mohsin, M. Umer, A. Bilal, M.A. Jamshed, D.F. Hougen, J.M. Cioffi. "6G Twin: Hybrid Gaussian Radio Fields for Channel Estimation and Non-Linear Precoder Design." **arXiv**, 2025. [[PDF]](https://arxiv.org/pdf/2509.18735)
27. A. Bilal, D. Ebert, B. Lin. "LLMs for Explainable AI: A Comprehensive Survey." **arXiv**, 2025. [[PDF]](https://arxiv.org/pdf/2504.00125)
28. A. Bilal, B. Lin. "Abstract — LLM for Explainable AI." **IEEE DSAA**, 2024 (poster).
29. A. Bilal, A. Salman, K. Khurshid, D.F. Hougen. "On Shadow Removal With Boosted Attention in a Vision Transformer." **Springer ML** (under review).
30. A. Bilal, A. Salman, K. Khurshid. "Person Identification using Gait with Fused Graph and 3D-CNN." **ACM TAIS** (under review).

</details>

## Honors

| Year | Honor |
|:---:|---|
| 2026 | Silver Reviewer Award — ICML 2026 |
| 2025 | Gallogly College of Engineering Graduate Fellowship |
| 2025 | Best Paper Award — ICC Workshop 2025, Montreal |
| 2025 | Honorary Certificate of Appreciation — IEEE ComSoc Student Competition *(Democratizing 6G)* |
| 2024 | Best Student Presentation Runner-up — IEEE DSAA'24 Student Forum |
| 2024 | Student Travel Grant — IEEE DSAA 2024, San Diego |
| 2024 | UGRIP Selection — MBZUAI, First Cohort |
| — | IEEE Emerging Young Researcher — IEEE Islamabad Section |

## Toolbox

<p align="center">
<img src="https://skillicons.dev/icons?i=py,anaconda,latex,cpp,c,java,matlab,pytorch,tensorflow,opencv,sklearn&theme=light" alt="Languages, ML & DL" />
<br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,git,github,linux,vscode,aws,nginx,raspberrypi,react,nextjs,js,html,css&theme=light" alt="Infra, MLOps & Web" />
<br/>
<img src="https://skillicons.dev/icons?i=figma,xd,ai,ps,wordpress&theme=light" alt="Design" />
</p>

**ML Techniques** — GRPO, LoRA, ZeRO, preference optimization, test-time scaling, LLM post-training, agentic systems
**Statistics & Theory** — Statistical learning theory, probabilistic modelling, information theory, optimization
**Core Competencies** — Signal processing, 5G, connectivity technologies, classification, distributed AI systems, MLflow, CUDA, Slurm, Cursor, pandas/NumPy

## GitHub Stats

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=AhsanBilal7&show_icons=true&hide_border=true&bg_color=0D1117&title_color=C77DA0&icon_color=C77DA0&text_color=c9d1d9" />
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=AhsanBilal7&show_icons=true&hide_border=true&bg_color=ffffff&title_color=7A1F3D&icon_color=7A1F3D&text_color=24292f" alt="GitHub Stats" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=AhsanBilal7&layout=compact&hide_border=true&bg_color=0D1117&title_color=C77DA0&text_color=c9d1d9" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AhsanBilal7&layout=compact&hide_border=true&bg_color=ffffff&title_color=7A1F3D&text_color=24292f" alt="Top Languages" />
</picture>
</p>

<div align="center">
<sub>Ahsan Bilal · University of Oklahoma · Stanford AI Lab · <a href="mailto:ahsan.bilal-1@ou.edu">ahsan.bilal-1@ou.edu</a></sub>
</div>
