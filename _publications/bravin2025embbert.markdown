---
layout: publication
title: 'Embbert-q: Breaking Memory Barriers In Embedded NLP'
authors: Riccardo Bravin, Massimo Pavan, Hazem Hesham Yousef Shalby, Fabrizio Pittorino, Manuel Roveri
conference: "Arxiv"
year: 2025
bibkey: bravin2025embbert
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.10001'}
  - {name: "Code", url: 'https://github.com/RiccardoBravin/tiny-LLM'}
tags: ['Has Code', 'Efficiency and Optimization', 'BERT', 'Applications', 'Model Architecture', 'Quantization', 'Reinforcement Learning']
---
Large Language Models (LLMs) have revolutionized natural language processing,
setting new standards across a wide range of applications. However, their
relevant memory and computational demands make them impractical for deployment
on technologically-constrained tiny devices such as wearable devices and
Internet-of-Things units. To address this limitation, we introduce EmbBERT-Q, a
novel tiny language model specifically designed for tiny devices with stringent
memory constraints. EmbBERT-Q achieves state-of-the-art (SotA) accuracy in
Natural Language Processing tasks in this scenario, with a total memory
footprint (weights and activations) of just 781 kB, representing a 25x
reduction in size with respect to SotA models. By combining architectural
innovations with hardware-compatible 8-bit quantization, EmbBERT-Q consistently
outperforms several baseline models scaled down to a 2 MB memory budget (i.e.,
the maximum memory typically available in tiny devices), including heavily
compressed versions of BERT and MAMBA. Extensive experimental evaluations on
both a selected benchmark dataset, TinyNLP, specifically curated to evaluate
Tiny Language Models in NLP tasks and real-world scenarios, and the GLUE
benchmark, demonstrate EmbBERT-Q ability to deliver competitive accuracy with
respect to existing approaches, achieving an unmatched balance between memory
and performance. To ensure the complete and immediate reproducibility of all
our results, we release all code, scripts, and model checkpoints at
https://github.com/RiccardoBravin/tiny-LLM.
