---
layout: publication
title: Can Better Text Semantics In Prompt Tuning Improve VLM Generalization
authors: Kuchibhotla Hari Chandana, Kancheti Sai Srinivas, Reddy Abbavaram Gowtham, Balasubramanian Vineeth N
conference: "Arxiv"
year: 2024
bibkey: kuchibhotla2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07921"}
tags: ['Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Going beyond mere fine-tuning of vision-language models (VLMs) learnable prompt tuning has emerged as a promising resource-efficient alternative. Despite their potential effectively learning prompts faces the following challenges (i) training in a low-shot scenario results in overfitting limiting adaptability and yielding weaker performance on newer classes or datasets; (ii) prompt-tunings efficacy heavily relies on the label space with decreased performance in large class spaces signaling potential gaps in bridging image and class concepts. In this work we investigate whether better text semantics can help address these concerns. In particular we introduce a prompt-tuning method that leverages class descriptions obtained from Large Language Models (LLMs). These class descriptions are used to bridge image and text modalities. Our approach constructs part-level description-guided image and text features which are subsequently aligned to learn more generalizable prompts. Our comprehensive experiments conducted across 11 benchmark datasets show that our method outperforms established methods demonstrating substantial improvements.
