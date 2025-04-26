---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
### Published papers

- SAFE-QAQ: End-to-End Slow-Thinking Audio-Text Fraud Detection via Reinforcement Learning
  
  **Peidong Wang<sup>\*</sup>**, Zhiming Ma<sup>\*</sup>, Xin Dai, YongKang Liu, Shi Feng, Xiaocui Yang, Daling Wang, Wenxing Hu, Zhihao Wang

  **Author ranking:** First Author

  **Contribution:** 
   * Proposed SAFE-QAQ, the first end-to-end fraud detection framework combining slow-thinking reasoning.
   * Introduced an optimization process, reducing reasoning lengths by 48.87\% without performance loss.
   * Developed a real-time detection system enabling 81.4\% faster detection (8.98s vs. 48.31s) while maintaining high accuracy.
  
  Submitted to ACM MM 2025 (under review)

- [TeleAntiFraud-28k: An Audio-Text Slow-Thinking Dataset for Telecom Fraud Detection (Submitted to ACM MM 2025)](https://arxiv.org/abs/2503.24115)
  
  Zhiming Ma<sup>\*</sup>, **Peidong Wang<sup>\*</sup>**, Minhua Huang, Jingpeng Wang, Kai Wu, Xiangzhao Lv, Yachun Pang, Yin Yang, Wenjie Tang, Yuchen Kang

  **Author ranking:** Co-first Author

  **Contribution:** 
   * Proposed TeleAntiFraud-28k, the first multi-task slow-thinking audio-language dataset for telecommunication fraud prevention.
   * Designed a pipeline using real-call ASR, LLM simulation, and multi-agent generation to maximize fraud coverage.
   * Established TeleAntiFraud-Bench, a benchmark for evaluating telecom fraud models with slow-thinking assessments.
  
  Submitted to ACM MM 2025 (under review)

- [Language Models as Continuous Self-Evolving Data Engineers](https://arxiv.org/abs/2412.15151)
  
  **Peidong Wang**, Ming Wang, Zhiming Ma, Xiaocui Yang, Shi Feng, Daling Wang, Yifei Zhang, Kaisong Song

  **Author ranking:** First Author

  **Contribution:** 
  * Proposed LANCE, a novel paradigm enabling LLMs to autonomously generate, clean, review, and annotate data for training themselves.
  * LANCE automates post-training data construction, improving efficiency, quality, and model performance across tasks by iterative self-training.
  * LANCE enhances mathematical reasoning, improving both basic and advanced tasks with general-purpose data.
  
  Submitted to ACL 2025 (under review)

- [STICKERCONV: Generating Multimodal Empathetic Responses from Scratch](https://neu-datamining.github.io/StickerConv/)

  Yiqun Zhang<sup>\*</sup>, Fanheng Kong<sup>\*</sup>, **Peidong Wang<sup>\*</sup>**, Shuang Sun, Lingshuai Wang,  Shi Feng, Daling Wang, Yifei Zhang, Kaisong Song

  **Author ranking:** Co-first Author

  **Contribution:** 
  * Introduced Agent4SC, a multi-agent framework that creates S{\small TICKER}C{\small ONV}, a multimodal empathetic dialogue dataset.
  * Designed [PEGS📌](https://github.com/ZhangYiqun018/StickerConv), a framework generating empathetic text and sticker responses based on emotional and contextual dynamics.
  * Proposed a method for evaluating multimodal empathetic responses, leveraging LLMs to assess empathy, consistency, and ranking quality.

  *Annual Meeting of the Association for Computational Linguistics(ACL 2024)* [CCF A] [[Home page]](https://neu-datamining.github.io/StickerConv/) [[PDF]](https://arxiv.org/pdf/2402.01679) [[GitHub]](https://github.com/ZhangYiqun018/StickerConv) [[arxiv]](https://arxiv.org/abs/2402.01679) [[🤗]](https://huggingface.co/datasets/NEUDM/StickerConv)

- [TIGER: A Unified Generative Model Framework for Multimodal Dialogue Response Generation](https://aclanthology.org/2024.lrec-main.1403/)

  Fanheng Kong, **Peidong Wang**, Shi Feng, Daling Wang, Yifei Zhang

  **Author ranking:** Second Author

  **Contribution:** 
  * Proposed TIGER, a unified generative framework for multimodal dialogue response generation with text and images.
  * Achieved state-of-the-art results on automatic and human evaluations, validating TIGER's effectiveness in multimodal conversations.

  *The 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)* [CCF B] [[PDF]](https://aclanthology.org/2024.lrec-main.1403.pdf) [[GitHub]](https://github.com/friedrichor/TIGER) [[Demo]](https://www.youtube.com/watch?v=Kd0CMwDs8Rk)