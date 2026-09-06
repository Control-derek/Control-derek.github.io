---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am **Peidong Wang (王培东)**, a direct-entry Ph.D. student in Computer Science at [Northeastern University](https://www.neu.edu.cn/) since September 2025, advised by [Associate Prof. Shi Feng](https://neu-datamining.github.io/cse/fengshi/) in the [Data Mining group](https://neu-datamining.github.io/).

My research focuses on **embodied AI, vision-language-action models (VLAs), and reinforcement learning for LLMs**. I am currently a foundation-model research intern at [XYZ AI Lab (行云至理研究院)](https://xyz-lab.ai/), working on Code Agent pre-training, RL, and training data. Previously, I interned at **Microsoft Research Asia (MSRA)** on embodied agents and LLM RL. I am mentored by **Xufang Luo** in both internships.

My work spans algorithm analysis, model training and data curation, and deployment on physical robots. I have first- or co-first-authored papers at **ACL, EMNLP, and ACM Multimedia**, with additional co-authored work in multimodal dialogue and reasoning.

[Research experience]({{ '/experience/' | relative_url }}) · [Publications]({{ '/publications/' | relative_url }}) · [中文简历 / Chinese CV]({{ '/cv/' | relative_url }})

## Research highlights

### Embodied agents and online robot learning

**[SHAPER](https://arxiv.org/abs/2608.11350)** evolves skills and an execution harness through environment rollouts while keeping model weights and low-level executors frozen. It improves VLABench success from **28.25% to 34.50%** and ESI-Bench accuracy from **32.5% to 49.8%**. The code is available as an [official Agent Lightning recipe](https://github.com/microsoft/agent-lightning/tree/v0.x/contrib/recipes/shaper).

On **SO-ARM101**, I work on VLA behavior cloning and online residual RL for tabletop manipulation. A π₀.₅ BC policy completed **39/39 trials across 13 placements** in a medicine-box stacking task. For precise toy-sword placement onto a stand, two-stage residual Actor-Critic learning improved success from **2/12 (16.7%) to 9/12 (75.0%)**.

### LLM RL and self-evolving systems

**ACPO** studies how off-policy degree changes importance-ratio clipping and token-level gradient dominance, then uses the analysis to design adaptive clipping for LLM reasoning. **[LANCE](https://aclanthology.org/2025.emnlp-main.914/)** connects self-evolving data agents with iterative model improvement. I am also a co-author of **[AI4AI at Scale](https://xyz-lab.ai/blogs/ai4ai-at-scale/assets/bounded-exploration-ai4ai-system-optimization.pdf)**, a technical report on agentic system optimization.

### Multimodal RL in practice

**[SAFE-QAQ](https://aclanthology.org/2026.acl-long.1201/)** combines audio-text reasoning, GRPO, and efficient inference for telecom fraud detection. Developed with China Mobile, the system is deployed in an anti-fraud production pipeline processing **over 70,000 calls per day**.

## Recent updates

- **2026:** SAFE-QAQ appeared at **ACL 2026**; SHAPER is available as a preprint and an Agent Lightning recipe; AI4AI at Scale is available as a technical report.
- **2026.05:** Started my foundation-model internship at **XYZ AI Lab**.
- **2025:** LANCE appeared at **EMNLP 2025**, and TeleAntiFraud-28k at **ACM Multimedia 2025**.
- **2025.09:** Started my Ph.D. at Northeastern University.

Earlier publications and competition results are listed on the [Publications]({{ '/publications/' | relative_url }}) and [Awards]({{ '/awards/' | relative_url }}) pages.
