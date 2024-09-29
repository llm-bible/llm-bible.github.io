---
layout: publication
title: Llmcad: Fast And Scalable On-device Large Language Model Inference
authors: Xu Daliang, Yin Wangsong, Jin Xin, Zhang Ying, Wei Shiyun, Xu Mengwei, Liu Xuanzhe
conference: "Arxiv"
year: 2023
bibkey: xu2023fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04255"}
tags: ['Applications', 'Language Modeling']
---
Generative tasks such as text generation and question answering hold a crucial position in the realm of mobile applications. Due to their sensitivity to privacy concerns there is a growing demand for their execution directly on mobile devices. Currently the execution of these generative tasks heavily depends on Large Language Models (LLMs). Nevertheless the limited memory capacity of these devices presents a formidable challenge to the scalability of such models. In our research we introduce LLMCad an innovative on-device inference engine specifically designed for efficient generative Natural Language Processing (NLP) tasks. The core idea behind LLMCad revolves around model collaboration a compact LLM residing in memory takes charge of generating the most straightforward tokens while a high-precision LLM steps in to validate these tokens and rectify any identified errors. LLMCad incorporates three novel techniques (1) Instead of generating candidate tokens in a sequential manner LLMCad employs the smaller LLM to construct a token tree encompassing a wider range of plausible token pathways. Subsequently the larger LLM can efficiently validate all of these pathways simultaneously. (2) It employs a self-adjusting fallback strategy swiftly initiating the verification process whenever the smaller LLM generates an erroneous token. (3) To ensure a continuous flow of token generation LLMCad speculatively generates tokens during the verification process by implementing a compute-IO pipeline. Through an extensive series of experiments LLMCad showcases an impressive token generation speed achieving rates up to 9.3x faster than existing inference engines.
