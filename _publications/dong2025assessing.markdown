---
layout: publication
title: 'MIRAGE: Assessing Hallucination In Multimodal Reasoning Chains Of MLLM'
authors: Bowen Dong, Minheng Ni, Zitong Huang, Guanglei Yang, Wangmeng Zuo, Lei Zhang
conference: "Arxiv"
year: 2025
bibkey: dong2025assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24238"}
tags: ['Multimodal Models', 'Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Multimodal hallucination in multimodal large language models (MLLMs) restricts the correctness of MLLMs. However, multimodal hallucinations are multi-sourced and arise from diverse causes. Existing benchmarks fail to adequately distinguish between perception-induced hallucinations and reasoning-induced hallucinations. This failure constitutes a significant issue and hinders the diagnosis of multimodal reasoning failures within MLLMs. To address this, we propose the \{\dataset\} benchmark, which isolates reasoning hallucinations by constructing questions where input images are correctly perceived by MLLMs yet reasoning errors persist. \{\dataset\} introduces multi-granular evaluation metrics: accuracy, factuality, and LLMs hallucination score for hallucination quantification. Our analysis reveals that (1) the model scale, data scale, and training stages significantly affect the degree of logical, fabrication, and factual hallucinations; (2) current MLLMs show no effective improvement on spatial hallucinations caused by misinterpreted spatial relationships, indicating their limited visual reasoning capabilities; and (3) question types correlate with distinct hallucination patterns, highlighting targeted challenges and potential mitigation strategies. To address these challenges, we propose \{\method\}, a method that combines curriculum reinforcement fine-tuning to encourage models to generate logic-consistent reasoning chains by stepwise reducing learning difficulty, and collaborative hint inference to reduce reasoning complexity. \{\method\} establishes a baseline on \{\dataset\}, and reduces the logical hallucinations in original base models.
