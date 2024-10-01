---
layout: publication
title: 'X-instructblip: A Framework For Aligning X-modal Instruction-aware Representations To Llms And Emergent Cross-modal Reasoning'
authors: Panagopoulou Artemis, Xue Le, Yu Ning, Li Junnan, Li Dongxu, Joty Shafiq, Xu Ran, Savarese Silvio, Xiong Caiming, Niebles Juan Carlos
conference: "Arxiv"
year: 2023
bibkey: panagopoulou2023x
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18799"}
tags: ['Fine Tuning', 'Multimodal Models', 'RAG', 'Tools']
---
Recent research has achieved significant advancements in visual reasoning tasks through learning image-to-language projections and leveraging the impressive reasoning abilities of Large Language Models (LLMs). This paper introduces an efficient and effective framework that integrates multiple modalities (images, 3D, audio and video) to a frozen LLM and demonstrates an emergent ability for cross-modal reasoning (2+ modality inputs). Our approach explores two distinct projection mechanisms: Q-Formers and Linear Projections (LPs). Through extensive experimentation across all four modalities on 16 benchmarks, we explore both methods and assess their adaptability in integrated and separate cross-modal reasoning. The Q-Former projection demonstrates superior performance in single modality scenarios and adaptability in joint versus discriminative reasoning involving two or more modalities. However, it exhibits lower generalization capabilities than linear projection in contexts where task-modality data are limited. To enable this framework, we devise a scalable pipeline that automatically generates high-quality, instruction-tuning datasets from readily available captioning data across different modalities, and contribute 24K QA data for audio and 250K QA data for 3D. To facilitate further research in cross-modal reasoning, we introduce the DisCRn (Discriminative Cross-modal Reasoning) benchmark comprising 9K audio-video QA samples and 28K image-3D QA samples that require the model to reason discriminatively across disparate input modalities.
