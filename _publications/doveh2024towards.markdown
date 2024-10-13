---
layout: publication
title: 'Towards Multimodal In-context Learning For Vision & Language Models'
authors: Doveh Sivan, Perek Shaked, Mirza M. Jehanzeb, Lin Wei, Alfassy Amit, Arbelle Assaf, Ullman Shimon, Karlinsky Leonid
conference: "Arxiv"
year: 2024
bibkey: doveh2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12736"}
tags: ['Few Shot', 'In Context Learning', 'Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
State-of-the-art Vision-Language Models (VLMs) ground the vision and the
language modality primarily via projecting the vision tokens from the encoder
to language-like tokens, which are directly fed to the Large Language Model
(LLM) decoder. While these models have shown unprecedented performance in many
downstream zero-shot tasks (eg image captioning, question answers, etc), still
little emphasis has been put on transferring one of the core LLM capability of
In-Context Learning (ICL). ICL is the ability of a model to reason about a
downstream task with a few examples demonstrations embedded in the prompt. In
this work, through extensive evaluations, we find that the state-of-the-art
VLMs somewhat lack the ability to follow ICL instructions. In particular, we
discover that even models that underwent large-scale mixed modality
pre-training and were implicitly guided to make use of interleaved image and
text information (intended to consume helpful context from multiple images)
under-perform when prompted with few-shot demonstrations (in an ICL way),
likely due to their lack of direct ICL instruction tuning. To enhance the ICL
abilities of the present VLM, we propose a simple yet surprisingly effective
multi-turn curriculum-based learning methodology with effective data mixes,
leading up to a significant 21.03% (and 11.3% on average) ICL performance boost
over the strongest VLM baselines and a variety of ICL benchmarks. Furthermore,
we also contribute new benchmarks for ICL evaluation in VLMs and discuss their
advantages over the prior art.
