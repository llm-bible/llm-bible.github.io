---
layout: publication
title: 'Enhancing Speech-to-speech Dialogue Modeling With End-to-end Retrieval-augmented Generation'
authors: Pengchao Feng, Ziyang Ma, Wenxi Chen, Yao Li, Sheng Wang, Kai Yu, Xie Chen
conference: "Arxiv"
year: 2025
bibkey: feng2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00028"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism']
---
In recent years, end-to-end speech-to-speech (S2S) dialogue systems have
garnered increasing research attention due to their advantages over traditional
cascaded systems, including achieving lower latency and more natural
integration of nonverbal cues such as emotion and speaker identity. However,
these end-to-end systems face key challenges, particularly in incorporating
external knowledge, a capability commonly addressed by Retrieval-Augmented
Generation (RAG) in text-based large language models (LLMs). The core
difficulty lies in the modality gap between input speech and retrieved textual
knowledge, which hinders effective integration. To address this issue, we
propose a novel end-to-end RAG framework that directly retrieves relevant
textual knowledge from speech queries, eliminating the need for intermediate
speech-to-text conversion via techniques like ASR. Experimental results
demonstrate that our method significantly improves the performance of
end-to-end S2S dialogue systems while achieving higher retrieval efficiency.
Although the overall performance still lags behind cascaded models, our
framework offers a promising direction for enhancing knowledge integration in
end-to-end S2S systems. We will release the code and dataset to support
reproducibility and promote further research in this area.
