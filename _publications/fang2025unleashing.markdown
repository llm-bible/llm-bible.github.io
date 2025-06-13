---
layout: publication
title: 'Geneda: Unleashing Generative Reasoning On Netlist Via Multimodal Encoder-decoder Aligned Foundation Model'
authors: Wenji Fang, Jing Wang, Yao Lu, Shang Liu, Zhiyao Xie
conference: "Arxiv"
year: 2025
bibkey: fang2025unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09485"}
tags: ['Tools', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Multimodal Models']
---
The success of foundation AI has motivated the research of circuit foundation
models, which are customized to assist the integrated circuit (IC) design
process. However, existing pre-trained circuit models are typically limited to
standalone encoders for predictive tasks or decoders for generative tasks.
These two model types are developed independently, operate on different circuit
modalities, and reside in separate latent spaces, which restricts their ability
to complement each other for more advanced applications. In this work, we
present GenEDA, the first framework that aligns circuit encoders with decoders
within a shared latent space. GenEDA bridges the gap between graph-based
circuit representations and text-based large language models (LLMs), enabling
communication between their respective latent spaces. To achieve the alignment,
we propose two paradigms that support both open-source trainable LLMs and
commercial frozen LLMs. Built on this aligned architecture, GenEDA enables
three unprecedented generative reasoning tasks over netlists, where the model
reversely generates the high-level functionality from low-level netlists in
different granularities. These tasks extend traditional gate-type prediction to
direct generation of full-circuit functionality. Experiments demonstrate that
GenEDA significantly boosts advanced LLMs' (e.g., GPT-4o and DeepSeek-V3)
performance in all tasks.
