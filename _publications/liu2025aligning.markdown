---
layout: publication
title: 'Aligning Vision To Language: Text-free Multimodal Knowledge Graph Construction For Enhanced Llms Reasoning'
authors: Junming Liu, Siyuan Meng, Yanting Gao, Song Mao, Pinlong Cai, Guohang Yan, Yirong Chen, Zilin Bian, Botian Shi, Ding Wang
conference: "Arxiv"
year: 2025
bibkey: liu2025aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.12972"}
  - {name: "Code", url: "https://github.com/Wings-Of-Disaster/VaLiK"}
tags: ['Efficiency and Optimization', 'Applications', 'RAG', 'Has Code', 'Multimodal Models']
---
Multimodal reasoning in Large Language Models (LLMs) struggles with
incomplete knowledge and hallucination artifacts, challenges that textual
Knowledge Graphs (KGs) only partially mitigate due to their modality isolation.
While Multimodal Knowledge Graphs (MMKGs) promise enhanced cross-modal
understanding, their practical construction is impeded by semantic narrowness
of manual text annotations and inherent noise in visual-semantic entity
linkages. In this paper, we propose Vision-align-to-Language integrated
Knowledge Graph (VaLiK), a novel approach for constructing MMKGs that enhances
LLMs reasoning through cross-modal information supplementation. Specifically,
we cascade pre-trained Vision-Language Models (VLMs) to align image features
with text, transforming them into descriptions that encapsulate image-specific
information. Furthermore, we developed a cross-modal similarity verification
mechanism to quantify semantic consistency, effectively filtering out noise
introduced during feature alignment. Even without manually annotated image
captions, the refined descriptions alone suffice to construct the MMKG.
Compared to conventional MMKGs construction paradigms, our approach achieves
substantial storage efficiency gains while maintaining direct entity-to-image
linkage capability. Experimental results on multimodal reasoning tasks
demonstrate that LLMs augmented with VaLiK outperform previous state-of-the-art
models. Our code is published at https://github.com/Wings-Of-Disaster/VaLiK.
