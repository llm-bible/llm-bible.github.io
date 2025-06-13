---
layout: publication
title: 'RCA: Region Conditioned Adaptation For Visual Abductive Reasoning'
authors: Hao Zhang, Yeo Keat Ee, Basura Fernando
conference: "Arxiv"
year: 2023
bibkey: zhang2023region
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.10428"}
  - {name: "Code", url: "https://github.com/LUNAProject22/RPA"}
tags: ['Fine-Tuning', 'Agentic', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Prompting']
---
Visual abductive reasoning aims to make likely explanations for visual
observations. We propose a simple yet effective Region Conditioned Adaptation,
a hybrid parameter-efficient fine-tuning method that equips the frozen CLIP
with the ability to infer explanations from local visual cues. We encode
``local hints'' and ``global contexts'' into visual prompts of the CLIP model
separately at fine and coarse-grained levels. Adapters are used for fine-tuning
CLIP models for downstream tasks and we design a new attention adapter, that
directly steers the focus of the attention map with trainable query and key
projections of a frozen CLIP model. Finally, we train our new model with a
modified contrastive loss to regress the visual feature simultaneously toward
features of literal description and plausible explanations. The loss enables
CLIP to maintain both perception and reasoning abilities. Experiments on the
Sherlock visual abductive reasoning benchmark show that the RCA significantly
outstands previous SOTAs, ranking the \nth\{1\} on the leaderboards (e.g., Human
Acc: RCA 31.74 \textit\{vs\} CPT-CLIP 29.58, higher =better). We also validate
the RCA is generalizable to local perception benchmarks like RefCOCO. We
open-source our project at
\textit\{\color\{magenta\}\{\url\{https://github.com/LUNAProject22/RPA\}\}\}.
