---
layout: archive
title: "Research & Robotics Experience"
permalink: /experience/
author_profile: true
---

## Research internships

### XYZ AI Lab (行云至理研究院)

**Foundation Model Research Intern · Shanghai · May 2026–present**<br>
Mentor: **Xufang Luo**

- Contribute to Code Agent pre-training, RL baselines, and data-to-training workflows. Work on filtering, rendering, deduplication, and scoring for four data types: non-PR commits, PR relations, review feedback, and code review.
- Scored **232 million commit samples** and built auditable relaxed/strict quality gates. Across task types, **62.9%–94.4% of candidates in calibration sets** failed the quality rules, informing pre-training and mid-training data selection.
- Co-authored **[AI4AI at Scale](https://xyz-lab.ai/blogs/ai4ai-at-scale/assets/bounded-exploration-ai4ai-system-optimization.pdf)** on bounded exploration and verification-gated agentic system optimization. The team released XYZ-Aquila-mini/pro Deep Search Agents with training, evaluation, and replay records.

### Microsoft Research Asia (MSRA)

**Research Intern · Shanghai · June 2025–May 2026**<br>
Mentor: **Xufang Luo**

- Study RLVR/GRPO updates through **ACPO**. Starting from conflicting findings about high-entropy and low-probability tokens, analyze how the number of updates per rollout changes off-policy degree, importance-ratio dispersion, and clipping behavior.
- Derive the relationship between token probability and importance-ratio variance, and characterize the conditional clipped gradient expectation to explain gradient dominance reversal. Use probability-bin-specific clipping thresholds informed by within-bin importance-ratio dispersion; evaluate on **3B/7B** models across mathematics, table QA, and logical reasoning.

## Embodied agents and physical robots

### SHAPER — Self-Evolving Embodied Agents via Skill-Harness Evolution

**First author · MSRA research project · 2026**<br>
[Paper](https://arxiv.org/abs/2608.11350) · [Agent Lightning recipe](https://github.com/microsoft/agent-lightning/tree/v0.x/contrib/recipes/shaper)

- Evolve skills and an execution harness through target-environment rollouts while keeping model parameters and low-level executors frozen, adapting embodied agents without weight updates.
- Improve **VLABench success from 28.25% to 34.50% (+6.25 pp)** and **ESI-Bench accuracy from 32.5% to 49.8% (+17.3 pp)**. The implementation was merged into Microsoft's Agent Lightning repository as an official recipe, covering training and evaluation on both benchmarks.

### SO-ARM101 — VLA Behavior Cloning & Online Reinforcement Learning

**Personal robotics project · 2026**<br>
LeRobot · OpenPI · π₀.₅ · ACT · SmolVLA · Residual RL

- Built a six-joint leader/follower robot setup with fixed and wrist cameras, **30 Hz teleoperation**, and remote inference. Collected **120 demonstrations / 25,316 frames** for stacking a medicine box onto a tea tin, with video/trajectory consistency checks, semantic quality review, idle-frame trimming, and training-set normalization.
- Conducted π₀.₅ full-parameter BC fine-tuning and physical evaluation. The medicine-box policy completed **39/39 trials (100.0%) across 13 placements** in the reported test batch.
- For grasping a toy sword and aligning it with a sword-stand slot, used a **frozen π₀.₅ and an offline-trained RL Token** with two-stage **TD3-style residual Actor-Critic** policies for grasping and placement. Online learning increased complete-task success from **2/12 (16.7%) with BC to 9/12 (75.0%) after RL**.

### ROBOCON 2022 — Motion Control

**October 2021–July 2022**<br>
National First Prize (Runner-up), “Create Brilliant Together” · National Third Prize, “Robot Equestrian”

- Combined Brown's triple exponential smoothing and Kalman filtering for moving-target prediction and delay compensation; used cubic B-splines and minimum-snap methods for two-robot trajectory planning.
- Developed reaction-wheel MPC and PID controllers for quadruped balance, with a three-state, three-step MPC formulation and constrained QPs using Eigen/OSQP. Completed **5 ms Linux–STM32F407 bench closed-loop integration** and contributed to embedded control and foot-end trajectory development.

## Multimodal RL and deployment

### SAFE-QAQ — Audio-Text Fraud Detection

**Co-first author · Northeastern University × China Mobile Internet · March–April 2025**<br>
ACL 2026 · [Paper](https://aclanthology.org/2026.acl-long.1201/) · [Code](https://github.com/Control-derek/SAFE-QAQ)

- Built an end-to-end audio-text reasoning framework using GRPO with rule-based rewards, followed by rejection-sampling fine-tuning and length-constrained RL for efficient reasoning.
- Deployed with China Mobile in a production anti-fraud pipeline processing **over 70,000 calls daily**. Achieved **87.49 average classification F1** on TeleAntiFraud-Bench with **48.87% shorter reasoning chains**; the chunk-based real-time variant reports **8.98 s average detection duration**.

## Skills

**Embodied AI & robotics:** LeRobot, OpenPI, ACT, SmolVLA, π₀.₅, residual RL, SO-ARM101, STM32, PID, MPC.<br>
**LLMs & training:** PyTorch, Transformers, RLVR/GRPO, off-policy RL, Code Agents, training data curation.
