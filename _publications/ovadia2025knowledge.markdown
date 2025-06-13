---
layout: publication
title: 'Knowledge-instruct: Effective Continual Pre-training From Limited Data Using Instructions'
authors: Oded Ovadia, Meni Brief, Rachel Lemberg, Eitam Sheetrit
conference: "Arxiv"
year: 2025
bibkey: ovadia2025knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05571"}
tags: ['Fine-Tuning', 'Training Techniques', 'RAG', 'Pre-Training']
---
While Large Language Models (LLMs) acquire vast knowledge during
pre-training, they often lack domain-specific, new, or niche information.
Continual pre-training (CPT) attempts to address this gap but suffers from
catastrophic forgetting and inefficiencies in low-data regimes. We introduce
Knowledge-Instruct, a novel approach to efficiently inject knowledge from
limited corpora through pure instruction-tuning. By generating
information-dense synthetic instruction data, it effectively integrates new
knowledge while preserving general reasoning and instruction-following
abilities. Knowledge-Instruct demonstrates superior factual memorization,
minimizes catastrophic forgetting, and remains scalable by leveraging synthetic
data from relatively small language models. Additionally, it enhances
contextual understanding, including complex multi-hop reasoning, facilitating
integration with retrieval systems. We validate its effectiveness across
diverse benchmarks, including Companies, a new dataset that we release to
measure knowledge injection capabilities.
