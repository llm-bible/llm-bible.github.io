---
layout: publication
title: 'Mars-po: Multi-agent Reasoning System Preference Optimization'
authors: Xiaoxuan Lou, Chaojie Wang, Bo An
conference: "Arxiv"
year: 2024
bibkey: lou2024mars
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.19039"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Mathematical reasoning is a fundamental capability for large language models
(LLMs), yet achieving high performance in this domain remains a significant
challenge. The auto-regressive generation process often makes LLMs susceptible
to errors, hallucinations, and inconsistencies, particularly during multi-step
reasoning. In this paper, we propose Mars-PO, a novel framework to improve the
mathematical reasoning capabilities of LLMs through a multi-agent system. It
combines high-quality outputs from multiple agents into a hybrid positive
sample set and pairs them with agent-specific negative samples to construct
robust preference pairs for training. By aligning agents with shared positive
samples while addressing individual weaknesses, Mars-PO achieves substantial
performance improvements on mathematical reasoning benchmarks. For example, it
increases the accuracy on the MATH benchmark of the state-of-the-art
instruction-tuned LLM, Llama3.1-8B-Instruct, from 50.38% to 57.82%.
Experimental results further demonstrate that our method consistently
outperforms other baselines, such as supervised fine-tuning, vanilla DPO, and
its enhanced versions, highlighting the effectiveness of our approach.
