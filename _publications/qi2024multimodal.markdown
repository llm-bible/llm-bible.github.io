---
layout: publication
title: SNIFFER Multimodal Large Language Model For Explainable Out45;of45;context Misinformation Detection
authors: Qi Peng, Yan Zehong, Hsu Wynne, Lee Mong Li
conference: "Arxiv"
year: 2024
bibkey: qi2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03170"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'RAG', 'Tools']
---
Misinformation is a prevalent societal issue due to its potential high risks. Out45;of45;context (OOC) misinformation where authentic images are repurposed with false text is one of the easiest and most effective ways to mislead audiences. Current methods focus on assessing image45;text consistency but lack convincing explanations for their judgments which is essential for debunking misinformation. While Multimodal Large Language Models (MLLMs) have rich knowledge and innate capability for visual reasoning and explanation generation they still lack sophistication in understanding and discovering the subtle crossmodal differences. In this paper we introduce SNIFFER a novel multimodal large language model specifically engineered for OOC misinformation detection and explanation. SNIFFER employs two45;stage instruction tuning on InstructBLIP. The first stage refines the models concept alignment of generic objects with news45;domain entities and the second stage leverages language45;only GPT45;4 generated OOC45;specific instruction data to fine45;tune the models discriminatory powers. Enhanced by external tools and retrieval SNIFFER not only detects inconsistencies between text and image but also utilizes external knowledge for contextual verification. Our experiments show that SNIFFER surpasses the original MLLM by over 4037; and outperforms state45;of45;the45;art methods in detection accuracy. SNIFFER also provides accurate and persuasive explanations as validated by quantitative and human evaluations.
