---
layout: publication
title: 'Towards Comprehensive Scene Understanding: Integrating First And Third-person Views For Lvlms'
authors: Insu Lee, Wooje Park, Jaeyun Jang, Minyoung Noh, Kyuhong Shim, Byonghyo Shim
conference: "Arxiv"
year: 2025
bibkey: lee2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21955'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Applications', 'Tools', 'Training Techniques', 'GPT', 'Prompting', 'Multimodal Models']
---
Large vision-language models (LVLMs) are increasingly deployed in interactive applications such as virtual and augmented reality, where first-person (egocentric) view captured by head-mounted cameras serves as key input. While this view offers fine-grained cues about user attention and hand-object interactions, their narrow field of view and lack of global context often lead to failures on spatially or contextually demanding queries. To address this, we introduce a framework that augments egocentric inputs with third-person (exocentric) views, providing complementary information such as global scene layout and object visibility to LVLMs. We present E3VQA, the first benchmark for multi-view question answering with 4K high-quality question-answer pairs grounded in synchronized ego-exo image pairs. Additionally, we propose M3CoT, a training-free prompting technique that constructs a unified scene representation by integrating scene graphs from three complementary perspectives. M3CoT enables LVLMs to reason more effectively across views, yielding consistent performance gains (4.84% for GPT-4o and 5.94% for Gemini 2.0 Flash) over a recent CoT baseline. Our extensive evaluation reveals key strengths and limitations of LVLMs in multi-view reasoning and highlights the value of leveraging both egocentric and exocentric inputs.
