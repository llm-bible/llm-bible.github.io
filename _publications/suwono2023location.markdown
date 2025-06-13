---
layout: publication
title: 'Location-aware Visual Question Generation With Lightweight Models'
authors: Nicholas Collin Suwono, Justin Chih-yao Chen, Tun Min Hung, Ting-hao Kenneth Huang, I-bin Liao, Yung-hui Li, Lun-wei Ku, Shao-hua Sun
conference: "Arxiv"
year: 2023
bibkey: suwono2023location
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15129"}
tags: ['BERT', 'RAG', 'GPT', 'Model Architecture']
---
This work introduces a novel task, location-aware visual question generation
(LocaVQG), which aims to generate engaging questions from data relevant to a
particular geographical location. Specifically, we represent such
location-aware information with surrounding images and a GPS coordinate. To
tackle this task, we present a dataset generation pipeline that leverages GPT-4
to produce diverse and sophisticated questions. Then, we aim to learn a
lightweight model that can address the LocaVQG task and fit on an edge device,
such as a mobile phone. To this end, we propose a method which can reliably
generate engaging questions from location-aware information. Our proposed
method outperforms baselines regarding human evaluation (e.g., engagement,
grounding, coherence) and automatic evaluation metrics (e.g., BERTScore,
ROUGE-2). Moreover, we conduct extensive ablation studies to justify our
proposed techniques for both generating the dataset and solving the task.
