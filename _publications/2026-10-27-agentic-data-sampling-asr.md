---
title: "Agentic Data Sampling Framework for Multilingual ASR via Linguistic-Aware Error-Driven Optimization"
collection: publications
category: conferences
permalink: /publication/2026-10-27-agentic-data-sampling-asr
excerpt: 'Proposed a linguistic-aware agentic data sampling framework that introduces a data sampling LLM agent into the multilingual ASR training loop. Experiments on twelve Common Voice languages with Whisper-medium show the method outperforms full-data training while using less data and lower computational resources.'
date: 2026-10-27
venue: 'The 21st National Conference on Man-machine Speech Communication (NCMMSC 2026)'
authors: 'Zhiheng Qian, Junhao Du, Jing Peng, Hanqi Li, Kunyang Peng, Feng Xue, Lu Chen, Shuai Wang, and Kai Yu'
paperurl: 'https://arxiv.org/pdf/2610.36538'
citation: 'Zhiheng Qian, Junhao Du, Jing Peng, Hanqi Li, Kunyang Peng, Feng Xue, Lu Chen, Shuai Wang, and Kai Yu. 2026. Agentic Data Sampling Framework for Multilingual ASR via Linguistic-Aware Error-Driven Optimization. In Proceedings of the 21st National Conference on Man-machine Speech Communication (NCMMSC 2026). arXiv preprint arXiv:2610.36538.'
---

Proposed a linguistic-aware agentic data sampling framework that introduces a data sampling LLM agent into the multilingual ASR training loop. The agent is driven by a linguistically grounded rubric that analyzes ASR errors from phonological, morphological, and syntactic perspectives, and uses the resulting feedback together with training statistics, budget constraints, and algorithm profiles to select domain-level, sample-level, and token-level sampling strategies.

**Key Contributions:**
(1) Proposed the agentic data sampling framework with a linguistically grounded error-analysis rubric;
(2) Conducted experiments on twelve Common Voice languages with Whisper-medium, showing performance better than full-data training with less training data, lower computational resources, and faster convergence.
