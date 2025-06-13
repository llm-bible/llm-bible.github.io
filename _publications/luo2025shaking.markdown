---
layout: publication
title: 'Shaking To Reveal: Perturbation-based Detection Of LLM Hallucinations'
authors: Jinyuan Luo, Zhen Fang, Yixuan Li, Seongheon Park, Ling Chen
conference: "Arxiv"
year: 2025
bibkey: luo2025shaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02696"}
tags: ['Tools', 'Ethics and Bias', 'Applications', 'RAG', 'TACL', 'Reinforcement Learning', 'ACL', 'Prompting']
---
Hallucination remains a key obstacle to the reliable deployment of large language models (LLMs) in real-world question answering tasks. A widely adopted strategy to detect hallucination, known as self-assessment, relies on the model's own output confidence to estimate the factual accuracy of its answers. However, this strategy assumes that the model's output distribution closely reflects the true data distribution, which may not always hold in practice. As bias accumulates through the model's layers, the final output can diverge from the underlying reasoning process, making output-level confidence an unreliable signal for hallucination detection. In this work, we propose Sample-Specific Prompting (SSP), a new framework that improves self-assessment by analyzing perturbation sensitivity at intermediate representations. These representations, being less influenced by model bias, offer a more faithful view of the model's latent reasoning process. Specifically, SSP dynamically generates noise prompts for each input and employs a lightweight encoder to amplify the changes in representations caused by the perturbation. A contrastive distance metric is then used to quantify these differences and separate truthful from hallucinated responses. By leveraging the dynamic behavior of intermediate representations under perturbation, SSP enables more reliable self-assessment. Extensive experiments demonstrate that SSP significantly outperforms prior methods across a range of hallucination detection benchmarks.
