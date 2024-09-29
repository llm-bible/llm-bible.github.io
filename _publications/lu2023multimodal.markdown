---
layout: publication
title: Multimodal Procedural Planning Via Dual Text45;image Prompting
authors: Lu Yujie, Lu Pan, Chen Zhiyu, Zhu Wanrong, Wang Xin Eric, Wang William Yang
conference: "Arxiv"
year: 2023
bibkey: lu2023multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.01795"}
  - {name: "Code", url: "https://github.com/YujieLu10/MPP"}
tags: ['Agentic', 'Has Code', 'Merging', 'Multimodal Models', 'Prompting', 'RAG']
---
Embodied agents have achieved prominent performance in following human instructions to complete tasks. However the potential of providing instructions informed by texts and images to assist humans in completing tasks remains underexplored. To uncover this capability we present the multimodal procedural planning (MPP) task in which models are given a high45;level goal and generate plans of paired text45;image steps providing more complementary and informative guidance than unimodal plans. The key challenges of MPP are to ensure the informativeness temporal coherenceand accuracy of plans across modalities. To tackle this we propose Text45;Image Prompting (TIP) a dual45;modality prompting method that jointly leverages zero45;shot reasoning ability in large language models (LLMs) and compelling text45;to45;image generation ability from diffusion45;based models. TIP improves the interaction in the dual modalities using Text45;to45;Image Bridge and Image45;to45;Text Bridge allowing LLMs to guide the textual45;grounded image plan generation and leveraging the descriptions of image plans to ground the textual plan reversely. To address the lack of relevant datasets we collect WIKIPLAN and RECIPEPLAN as a testbed for MPP. Our results show compelling human preferences and automatic scores against unimodal and multimodal baselines on WIKIPLAN and RECIPEPLAN in terms of informativeness temporal coherence and plan accuracy. Our code and data https://github.com/YujieLu10/MPP.
