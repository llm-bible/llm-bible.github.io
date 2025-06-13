---
layout: publication
title: 'How Llms Learn: Tracing Internal Representations With Sparse Autoencoders'
authors: Tatsuro Inaba, Kentaro Inui, Yusuke Miyao, Yohei Oseki, Benjamin Heinzerling, Yu Takagi
conference: "Arxiv"
year: 2025
bibkey: inaba2025how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.06394'}
tags: ['Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) demonstrate remarkable multilingual capabilities
and broad knowledge. However, the internal mechanisms underlying the
development of these capabilities remain poorly understood. To investigate
this, we analyze how the information encoded in LLMs' internal representations
evolves during the training process. Specifically, we train sparse autoencoders
at multiple checkpoints of the model and systematically compare the
interpretative results across these stages. Our findings suggest that LLMs
initially acquire language-specific knowledge independently, followed by
cross-linguistic correspondences. Moreover, we observe that after mastering
token-level knowledge, the model transitions to learning higher-level, abstract
concepts, indicating the development of more conceptual understanding.
