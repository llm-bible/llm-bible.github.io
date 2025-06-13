---
layout: publication
title: 'PUB: A Pragmatics Understanding Benchmark For Assessing Llms'' Pragmatics Capabilities'
authors: Settaluri Lakshmi Sravanthi, Meet Doshi, Tankala Pavan Kalyan, Rudra Murthy, Pushpak Bhattacharyya, Raj Dabre
conference: "Arxiv"
year: 2024
bibkey: sravanthi2024pragmatics
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07078"}
tags: ['Fine-Tuning', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
LLMs have demonstrated remarkable capability for understanding semantics, but
they often struggle with understanding pragmatics. To demonstrate this fact, we
release a Pragmatics Understanding Benchmark (PUB) dataset consisting of
fourteen tasks in four pragmatics phenomena, namely, Implicature,
Presupposition, Reference, and Deixis. We curated high-quality test sets for
each task, consisting of Multiple Choice Question Answers (MCQA). PUB includes
a total of 28k data points, 6.1k of which have been created by us, and the rest
are adapted from existing datasets. We evaluated nine models varying in the
number of parameters and type of training. Our study indicates that fine-tuning
for instruction-following and chat significantly enhances the pragmatics
capabilities of smaller language models. However, for larger models, the base
versions perform comparably with their chat-adapted counterparts. Additionally,
there is a noticeable performance gap between human capabilities and model
capabilities. Furthermore, unlike the consistent performance of humans across
various tasks, the models demonstrate variability in their proficiency, with
performance levels fluctuating due to different hints and the complexities of
tasks within the same dataset. Overall, the benchmark aims to provide a
comprehensive evaluation of LLM's ability to handle real-world language tasks
that require pragmatic reasoning.
