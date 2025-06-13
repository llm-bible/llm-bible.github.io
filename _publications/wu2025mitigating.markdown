---
layout: publication
title: 'Mitigating Hallucinations In Large Vision-language Models Via Entity-centric Multimodal Preference Optimization'
authors: Jiulong Wu, Zhengliang Shi, Shuaiqiang Wang, Jizhou Huang, Dawei Yin, Lingyong Yan, Min Cao, Min Zhang
conference: "Arxiv"
year: 2025
bibkey: wu2025mitigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.04039'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Multimodal Models']
---
Large Visual Language Models (LVLMs) have demonstrated impressive capabilities across multiple tasks. However, their trustworthiness is often challenged by hallucinations, which can be attributed to the modality misalignment and the inherent hallucinations of their underlying Large Language Models (LLMs) backbone. Existing preference alignment methods focus on aligning model responses with human preferences while neglecting image-text modality alignment, resulting in over-reliance on LLMs and hallucinations. In this paper, we propose Entity-centric Multimodal Preference Optimization (EMPO), which achieves enhanced modality alignment than existing human preference alignment methods. Besides, to overcome the scarcity of high-quality multimodal preference data, we utilize open-source instruction datasets to automatically construct high-quality preference data across three aspects: image, instruction, and response. Experiments on two human preference datasets and five multimodal hallucination benchmarks demonstrate the effectiveness of EMPO, e.g., reducing hallucination rates by 85.9% on Object-HalBench and 49.8% on MM-HalBench.
