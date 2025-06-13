---
layout: publication
title: 'MAGNET: Augmenting Generative Decoders With Representation Learning And Infilling Capabilities'
authors: Savya Khosla, Aditi Tiwari, Kushal Kafle, Simon Jenni, Handong Zhao, John Collomosse, Jing Shi
conference: "Arxiv"
year: 2025
bibkey: khosla2025augmenting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.08648"}
tags: ['Transformer', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
While originally designed for unidirectional generative modeling,
decoder-only large language models (LLMs) are increasingly being adapted for
bidirectional modeling. However, unidirectional and bidirectional models are
typically trained separately with distinct objectives (generation and
representation learning). This separation overlooks the opportunity for
developing a more versatile language model and for these objectives to
complement each other. In this work, we propose MAGNET, a method for adapting
decoder-only LLMs to generate robust representations and infill missing text
spans. MAGNET employs three self-supervised training objectives and introduces
an attention mechanism that combines bidirectional and causal attention,
enabling unified training across all objectives. Our results demonstrate that
LLMs adapted with MAGNET (1) surpass strong text encoders on token-level and
sentence-level representation learning tasks, (2) generate contextually
appropriate text infills by leveraging past and future contexts, (3) perform
open-ended text generation without excessive repetition of words or phrases,
and (4) preserve the knowledge and reasoning capability gained by the LLM
during pretraining.
