---
layout: publication
title: Towards Multimodal In45;context Learning For Vision amp; Language Models
authors: Doveh Sivan, Perek Shaked, Mirza M. Jehanzeb, Lin Wei, Alfassy Amit, Arbelle Assaf, Ullman Shimon, Karlinsky Leonid
conference: "Arxiv"
year: 2024
bibkey: doveh2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12736"}
tags: ['Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
State45;of45;the45;art Vision45;Language Models (VLMs) ground the vision and the language modality primarily via projecting the vision tokens from the encoder to language45;like tokens which are directly fed to the Large Language Model (LLM) decoder. While these models have shown unprecedented performance in many downstream zero45;shot tasks (eg image captioning question answers etc) still little emphasis has been put on transferring one of the core LLM capability of In45;Context Learning (ICL). ICL is the ability of a model to reason about a downstream task with a few examples demonstrations embedded in the prompt. In this work through extensive evaluations we find that the state45;of45;the45;art VLMs somewhat lack the ability to follow ICL instructions. In particular we discover that even models that underwent large45;scale mixed modality pre45;training and were implicitly guided to make use of interleaved image and text information (intended to consume helpful context from multiple images) under45;perform when prompted with few45;shot demonstrations (in an ICL way) likely due to their lack of direct ICL instruction tuning. To enhance the ICL abilities of the present VLM we propose a simple yet surprisingly effective multi45;turn curriculum45;based learning methodology with effective data mixes leading up to a significant 21.0337; (and 11.337; on average) ICL performance boost over the strongest VLM baselines and a variety of ICL benchmarks. Furthermore we also contribute new benchmarks for ICL evaluation in VLMs and discuss their advantages over the prior art.
