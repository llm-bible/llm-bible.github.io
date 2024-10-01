---
layout: publication
title: 'Analyzing Chain-of-thought Prompting In Large Language Models Via Gradient-based Feature Attributions'
authors: Wu Skyler, Shen Eric Meng, Badrinath Charumathi, Ma Jiaqi, Lakkaraju Himabindu
conference: "Arxiv"
year: 2023
bibkey: wu2023analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.13339"}
tags: ['Applications', 'Few Shot', 'In Context Learning', 'Prompting', 'RAG', 'Security']
---
Chain-of-thought (CoT) prompting has been shown to empirically improve the accuracy of large language models (LLMs) on various question answering tasks. While understanding why CoT prompting is effective is crucial to ensuring that this phenomenon is a consequence of desired model behavior, little work has addressed this; nonetheless, such an understanding is a critical prerequisite for responsible model deployment. We address this question by leveraging gradient-based feature attribution methods which produce saliency scores that capture the influence of input tokens on model output. Specifically, we probe several open-source LLMs to investigate whether CoT prompting affects the relative importances they assign to particular input tokens. Our results indicate that while CoT prompting does not increase the magnitude of saliency scores attributed to semantically relevant tokens in the prompt compared to standard few-shot prompting, it increases the robustness of saliency scores to question perturbations and variations in model output.
