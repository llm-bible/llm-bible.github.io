---
layout: publication
title: 'The Power Of Question Translation Training In Multilingual Reasoning: Broadened Scope And Deepened Insights'
authors: Wenhao Zhu, Shujian Huang, Fei Yuan, Cheng Chen, Jiajun Chen, Alexandra Birch
conference: "Arxiv"
year: 2024
bibkey: zhu2024power
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01345"}
tags: ['RAG', 'Training Techniques', 'Tools']
---
Bridging the significant gap between large language model's English and
non-English performance presents a great challenge. While some previous studies
attempt to mitigate this gap with translated training data, the recently
proposed question alignment framework leverages the model's English expertise
to improve multilingual performance with minimum usage of expensive,
error-prone translation. In this paper, we explore how broadly this method can
be applied by examining its effects in reasoning with and without
chain-of-thought, as well as with program-of-thought. We also explore applying
this framework to extremely large language models in an efficient manner, such
as through proxy-tuning. Experiment results on multilingual reasoning
benchmarks mGSM, mSVAMP, xCSQA and xNLI demonstrate that we can extend question
alignment framework to boost multilingual performance across diverse reasoning
scenarios, model families, and sizes. For instance, when applied to the LLaMA2
models, it brings an average accuracy improvements of 12.2% on mGSM even with
the 70B model. To understand the mechanism of its success, we analyze
representation space, generated response and data scales, and reveal how
question translation training strengthens language alignment within LLMs and
shapes their working patterns.
