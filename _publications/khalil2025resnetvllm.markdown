---
layout: publication
title: 'Resnetvllm-2: Addressing Resnetvllm''s Multi-modal Hallucinations'
authors: Ahmad Khalil, Mahmoud Khalil, Alioune Ngom
conference: "Arxiv"
year: 2025
bibkey: khalil2025resnetvllm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14429'}
tags: ['RAG']
---
Large Language Models (LLMs) have transformed natural language processing
(NLP) tasks, but they suffer from hallucination, generating plausible yet
factually incorrect content. This issue extends to Video-Language Models
(VideoLLMs), where textual descriptions may inaccurately represent visual
content, resulting in multi-modal hallucinations. In this paper, we address
hallucination in ResNetVLLM, a video-language model combining ResNet visual
encoders with LLMs. We introduce a two-step protocol: (1) a faithfulness
detection strategy that uses a modified Lynx model to assess semantic alignment
between generated captions and ground-truth video references, and (2) a
hallucination mitigation strategy using Retrieval-Augmented Generation (RAG)
with an ad-hoc knowledge base dynamically constructed during inference. Our
enhanced model, ResNetVLLM-2, reduces multi-modal hallucinations by
cross-verifying generated content against external knowledge, improving factual
consistency. Evaluation on the ActivityNet-QA benchmark demonstrates a
substantial accuracy increase from 54.8% to 65.3%, highlighting the
effectiveness of our hallucination detection and mitigation strategies in
enhancing video-language model reliability.
