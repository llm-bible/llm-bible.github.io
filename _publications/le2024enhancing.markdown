---
layout: publication
title: 'Molx: Enhancing Large Language Models For Molecular Learning With A Multi-modal Extension'
authors: Khiem Le, Zhichun Guo, Kaiwen Dong, Xiaobao Huang, Bozhao Nan, Roshni Iyer, Xiangliang Zhang, Olaf Wiest, Wei Wang, Nitesh V. Chawla
conference: "Arxiv"
year: 2024
bibkey: le2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06777"}
tags: ['Fine-Tuning', 'Applications', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) with their strong task-handling capabilities
have shown remarkable advancements across a spectrum of fields, moving beyond
natural language understanding. However, their proficiency within the chemistry
domain remains restricted, especially in solving professional molecule-related
tasks. This challenge is attributed to their inherent limitations in
comprehending molecules using only common textual representations, i.e., SMILES
strings. In this study, we seek to enhance the ability of LLMs to comprehend
molecules by equipping them with a multi-modal external module, namely MolX. In
particular, instead of directly using a SMILES string to represent a molecule,
we utilize specific encoders to extract fine-grained features from both SMILES
string and 2D molecular graph representations for feeding into an LLM.
Moreover, a handcrafted molecular fingerprint is incorporated to leverage its
embedded domain knowledge. Then, to establish an alignment between MolX and the
LLM's textual input space, the whole model in which the LLM is frozen, is
pre-trained with a versatile strategy including a diverse set of tasks.
Experimental evaluations show that our proposed method outperforms baselines
across 4 downstream molecule-related tasks ranging from molecule-to-text
translation to retrosynthesis, with and without fine-tuning the LLM, while only
introducing a small number of trainable parameters 0.53% and 0.82%,
respectively.
