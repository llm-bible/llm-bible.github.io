---
layout: publication
title: 'CERET: Cost-effective Extrinsic Refinement For Text Generation'
authors: Jason Cai, Hang Su, Monica Sunkara, Igor Shalyminov, Saab Mansour
conference: "Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics Human Language Technologies (Volume 1 Long Papers)"
year: 2024
bibkey: cai2024cost
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05588"}
tags: ['Fine-Tuning', 'Applications', 'Language Modeling', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) are powerful models for generation tasks, but
they may not generate good quality outputs in their first attempt. Apart from
model fine-tuning, existing approaches to improve prediction accuracy and
quality typically involve LLM self-improvement / self-reflection that
incorporate feedback from models themselves. Despite their effectiveness, these
methods are hindered by their high computational cost and lack of scalability.
In this work, we propose CERET, a method for refining text generations by
considering semantic stability, entailment and inter-sample uncertainty
measures. Experimental results show that CERET outperforms Self-consistency and
Self-rerank baselines consistently under various task setups, by ~1.6% in
Rouge-1 for abstractive summarization and ~3.5% in hit rate for question
answering. Compared to LLM Self-rerank method, our approach only requires 9.4%
of its latency and is more cost-effective.
