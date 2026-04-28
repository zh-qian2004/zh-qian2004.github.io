---
title: "Phonetic forced alignment for low-resource language varieties: Model training and evaluation on Chengdu Mandarin"
collection: publications
category: conferences
permalink: /publication/2026-03-01-forced-alignment-chengdu
excerpt: 'Developed a robust phonetic forced alignment system for Chengdu Mandarin. Devised a bootstrapping pipeline that leverages GMM-HMM generated pseudo-labels to fine-tune Wav2Vec2 for text-independent alignment, demonstrating SOTA performance against existing baselines on Chengdu Mandarin.'
date: 2026-03-01
venue: 'Submitted to Interspeech 2026'
citation: 'Zhiheng Qian, Aini Li, Hai Hu, and Liang Zhao. 2026. Phonetic Forced Alignment for Low-Resource Language Varieties: Model Training and Evaluation on Chengdu Mandarin. Submitted to Interspeech 2026.'
---

Developed a robust phonetic forced alignment system for Chengdu Mandarin. Devised a bootstrapping pipeline that leverages GMM-HMM generated pseudo-labels to fine-tune Wav2Vec2 for text-independent alignment, demonstrating SOTA performance against existing baselines on Chengdu Mandarin.

**Key Contributions:**
(1) Proposed a bootstrapping pipeline for low-resource, text-independent phonetic alignment tasks;
(2) Compiled a Chengdu Mandarin Grapheme-to-Phoneme dictionary to support model training;
(3) Trained a GMM-HMM aligner to generate pseudo-labels, which were then used to fine-tune Wav2Vec2 for superior feature extraction;
(4) Conducted evaluations demonstrating that our released Chengdu Mandarin forced aligner significantly outperforms standard baselines, establishing a new SOTA for Chengdu Mandarin forced alignment.