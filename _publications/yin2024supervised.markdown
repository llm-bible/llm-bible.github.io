---
layout: publication
title: 'SEA: Supervised Embedding Alignment For Token-level Visual-textual Integration In Mllms'
authors: Yin Yuanyang, Zhao Yaqi, Zhang Yajie, Lin Ke, Wang Jiahao, Tao Xin, Wan Pengfei, Zhang Di, Yin Baoqun, Zhang Wentao
conference: "Arxiv"
year: 2024
bibkey: yin2024supervised
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11813"}
tags: ['Interpretability And Explainability', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Multimodal Large Language Models (MLLMs) have recently demonstrated
remarkable perceptual and reasoning abilities, typically comprising a Vision
Encoder, an Adapter, and a Large Language Model (LLM). The adapter serves as
the critical bridge between the visual and language components. However,
training adapters with image-level supervision often results in significant
misalignment, undermining the LLMs' capabilities and limiting the potential of
Multimodal LLMs. To address this, we introduce Supervised Embedding Alignment
(SEA), a token-level alignment method that leverages vision-language
pre-trained models, such as CLIP, to align visual tokens with the LLM's
embedding space through contrastive learning. This approach ensures a more
coherent integration of visual and language representations, enhancing the
performance and interpretability of multimodal LLMs while preserving their
inherent capabilities. Extensive experiments show that SEA effectively improves
MLLMs, particularly for smaller models, without adding extra data or inference
computation. SEA also lays the groundwork for developing more general and
adaptable solutions to enhance multimodal systems.
