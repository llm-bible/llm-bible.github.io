---
layout: publication
title: 'Adaptive Inner Speech-text Alignment For Llm-based Speech Translation'
authors: Henglyu Liu, Andong Chen, Kehai Chen, Xuefeng Bai, Meizhi Zhong, Yuan Qiu, Min Zhang
conference: "Arxiv"
year: 2025
bibkey: liu2025adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10211"}
tags: ['RAG', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning']
---
Recent advancement of large language models (LLMs) has led to significant
breakthroughs across various tasks, laying the foundation for the development
of LLM-based speech translation systems. Existing methods primarily focus on
aligning inputs and outputs across modalities while overlooking deeper semantic
alignment within model representations. To address this limitation, we propose
an Adaptive Inner Speech-Text Alignment (AI-STA) method to bridge the modality
gap by explicitly aligning speech and text representations at selected layers
within LLMs. To achieve this, we leverage the optimal transport (OT) theory to
quantify fine-grained representation discrepancies between speech and text.
Furthermore, we utilize the cross-modal retrieval technique to identify the
layers that are best suited for alignment and perform joint training on these
layers. Experimental results on speech translation (ST) tasks demonstrate that
AI-STA significantly improves the translation performance of large speech-text
models (LSMs), outperforming previous state-of-the-art approaches. Our findings
highlight the importance of inner-layer speech-text alignment in LLMs and
provide new insights into enhancing cross-modal learning.
