---
layout: publication
title: 'Unimot: Unified Molecule-text Language Model With Discrete Token Representation'
authors: Juzheng Zhang, Yatao Bian, Yongqiang Chen, Quanming Yao
conference: "Arxiv"
year: 2024
bibkey: zhang2024unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.00863"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Quantization', 'Pretraining Methods', 'Applications']
---
The remarkable success of Large Language Models (LLMs) across diverse tasks
has driven the research community to extend their capabilities to molecular
applications. However, most molecular LLMs employ adapter-based architectures
that do not treat molecule and text modalities equally and lack a supervision
signal for the molecule modality. To address these issues, we introduce UniMoT,
a Unified Molecule-Text LLM adopting a tokenizer-based architecture that
expands the vocabulary of LLM with molecule tokens. Specifically, we introduce
a Vector Quantization-driven tokenizer that incorporates a Q-Former to bridge
the modality gap between molecule and text. This tokenizer transforms molecules
into sequences of molecule tokens with causal dependency, encapsulating
high-level molecular and textual information. Equipped with this tokenizer,
UniMoT can unify molecule and text modalities under a shared token
representation and an autoregressive training paradigm, enabling it to
interpret molecules as a foreign language and generate them as text. Following
a four-stage training scheme, UniMoT emerges as a multi-modal generalist
capable of performing both molecule-to-text and text-to-molecule tasks.
Extensive experiments demonstrate that UniMoT achieves state-of-the-art
performance across a wide range of molecule comprehension and generation tasks.
