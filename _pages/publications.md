---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

Selected work on embodied agents, reinforcement learning, self-evolving data systems, and multimodal reasoning. <sup>*</sup> denotes equal contribution.

## Preprints & Technical Reports

### [Self-Evolving Embodied Agents via Skill-Harness Evolution](https://arxiv.org/abs/2608.11350)

**Peidong Wang**, Zhiming Ma, Ying Chang, Xufang Luo, Xiaocui Yang, Shi Feng, Yuqing Yang, Dongsheng Li

**SHAPER · arXiv, 2026 · Under review**<br>
*Embodied Agents · VLA · Skill-Harness Evolution*

SHAPER adapts embodied agents through target-environment rollouts that evolve reusable skills and an execution harness while keeping model parameters and low-level executors frozen. VLABench success improves from **28.25% to 34.50%**, and ESI-Bench accuracy from **32.5% to 49.8%**. The implementation is available as an official recipe in Microsoft's Agent Lightning repository.

[[Paper]](https://arxiv.org/abs/2608.11350) [[Agent Lightning recipe]](https://github.com/microsoft/agent-lightning/tree/v0.x/contrib/recipes/shaper)

### [AI4AI at Scale: A Full-Pipeline System for Enhancing LLM Agentic Capabilities](https://xyz-lab.ai/blogs/ai4ai-at-scale/assets/bounded-exploration-ai4ai-system-optimization.pdf)

**Technical report, 2026 · Co-author**<br>
*Foundation Model Post-Training · Agentic System Optimization*

I contributed as an author during my foundation-model internship at XYZ AI Lab. The report describes bounded exploration and verification-gated agentic system optimization; the team released XYZ-Aquila-mini/pro Deep Search Agents together with training, evaluation, and replay records.

[[Report]](https://xyz-lab.ai/blogs/ai4ai-at-scale/assets/bounded-exploration-ai4ai-system-optimization.pdf)

### What Are Key Factors for Updates in RL for LLM Reasoning?

**ACPO · Under review, 2026**<br>
*LLM RL · Off-Policy Optimization · Theoretical Analysis*

Starting from conflicting observations about token-level updates, we analyze how off-policy degree, token probability, and importance-ratio clipping affect gradient magnitude and direction. The analysis motivates ACPO, which groups tokens by behavior-policy probability and adapts clipping bounds using within-group importance-ratio dispersion. Experiments cover **3B/7B** models on mathematics, table question answering, and logical reasoning under near- and off-policy settings.

## Published Papers

### [SAFE-QAQ: End-to-End Slow-Thinking Audio-Text Fraud Detection via Reinforcement Learning](https://aclanthology.org/2026.acl-long.1201/)

**Peidong Wang<sup>*</sup>**, Zhiming Ma<sup>*</sup>, Xin Dai<sup>*</sup>, Yongkang Liu, Shi Feng, Xiaocui Yang, Wenxing Hu, Zhihao Wang, Mingjun Pan, Li Yuan, Daling Wang

**ACL 2026**<br>
*Multimodal RL · Audio Reasoning · GRPO*

An end-to-end audio-text fraud detection framework with rule-based reasoning rewards and efficient, chunk-based risk assessment. Deployed in China Mobile's anti-fraud business pipeline, it processes **over 70,000 calls daily**. SAFE-QAQ achieves **87.49 average classification F1** on TeleAntiFraud-Bench and reduces reasoning length by **48.87%**; its real-time variant detects risk in **8.98 seconds on average**.

[[Paper]](https://aclanthology.org/2026.acl-long.1201/) [[PDF]](https://aclanthology.org/2026.acl-long.1201.pdf) [[Code]](https://github.com/Control-derek/SAFE-QAQ)

### [Language Models as Continuous Self-Evolving Data Engineers](https://aclanthology.org/2025.emnlp-main.914/)

**Peidong Wang**, Ming Wang, Zhiming Ma, Xiaocui Yang, Shi Feng, Daling Wang, Yifei Zhang, Kaisong Song

**EMNLP 2025**<br>
*Recursive Self-Improvement · Data Agents*

LANCE enables language models to generate, clean, review, and annotate their own training data with preference information. Iterative self-training connects data construction with model improvement, reducing reliance on external supervision for post-training data.

[[Paper]](https://aclanthology.org/2025.emnlp-main.914/) [[PDF]](https://aclanthology.org/2025.emnlp-main.914.pdf) [[Code]](https://github.com/Control-derek/LANCE)

### [TeleAntiFraud-28k: An Audio-Text Slow-Thinking Dataset for Telecom Fraud Detection](https://arxiv.org/abs/2503.24115)

Zhiming Ma<sup>*</sup>, **Peidong Wang<sup>*</sup>**, Minhua Huang, Jingpeng Wang, Kai Wu, Xiangzhao Lv, Yachun Pang, Yin Yang, Wenjie Tang, Yuchen Kang

**ACM Multimedia 2025**<br>
*Audio-Text Dataset · Fraud Detection Benchmark*

A multi-task audio-text dataset for telecom fraud detection, built through real-call transcription, LLM simulation, and multi-agent generation. The accompanying TeleAntiFraud-Bench evaluates fraud detection and slow-thinking audio-language reasoning.

[[Paper]](https://arxiv.org/abs/2503.24115) [[Code & Data]](https://github.com/JimmyMa99/TeleAntiFraud)

### [STICKERCONV: Generating Multimodal Empathetic Responses from Scratch](https://aclanthology.org/2024.acl-long.417/)

Yiqun Zhang<sup>*</sup>, Fanheng Kong<sup>*</sup>, **Peidong Wang<sup>*</sup>**, Shuang Sun, Lingshuai Wang, Shi Feng, Daling Wang, Yifei Zhang, Kaisong Song

**ACL 2024**<br>
*Multimodal LLMs · Multi-Agent Systems · Empathetic Dialogue*

Agent4SC uses collaborative agents to construct a multimodal empathetic dialogue dataset. The PEGS framework generates contextually relevant text and sticker responses, supported by LLM-based evaluation of empathy and consistency.

[[Paper]](https://aclanthology.org/2024.acl-long.417/) [[Project]](https://neu-datamining.github.io/StickerConv/) [[Code]](https://github.com/ZhangYiqun018/StickerConv) [[Dataset]](https://huggingface.co/datasets/NEUDM/StickerConv)

### [TIGER: A Unified Generative Model Framework for Multimodal Dialogue Response Generation](https://aclanthology.org/2024.lrec-main.1403/)

Fanheng Kong, **Peidong Wang**, Shi Feng, Daling Wang, Yifei Zhang

**LREC-COLING 2024**<br>
*Multimodal Dialogue · Response Generation*

A unified generative framework for dialogue responses containing both text and images, evaluated through automatic metrics and human judgments.

[[Paper]](https://aclanthology.org/2024.lrec-main.1403/) [[PDF]](https://aclanthology.org/2024.lrec-main.1403.pdf) [[Code]](https://github.com/friedrichor/TIGER) [[Demo]](https://www.youtube.com/watch?v=Kd0CMwDs8Rk)
