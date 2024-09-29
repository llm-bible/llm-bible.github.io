---
layout: publication
title: Lamda Large Model Fine45;tuning Via Spectrally Decomposed Low45;dimensional Adaptation
authors: Azizi Seyedarmin, Kundu Souvik, Pedram Massoud
conference: "Arxiv"
year: 2024
bibkey: azizi2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12832"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'RAG', 'Reinforcement Learning']
---
Low45;rank adaptation (LoRA) has become the default approach to fine45;tune large language models (LLMs) due to its significant reduction in trainable parameters. However trainable parameter demand for LoRA increases with increasing model embedding dimensions leading to high compute costs. Additionally its backward updates require storing high45;dimensional intermediate activations and optimizer states demanding high peak GPU memory. In this paper we introduce large model fine45;tuning via spectrally decomposed low45;dimensional adaptation (LaMDA) a novel approach to fine45;tuning large language models which leverages low45;dimensional adaptation to achieve significant reductions in trainable parameters and peak GPU memory footprint. LaMDA freezes a first projection matrix (PMA) in the adaptation path while introducing a low45;dimensional trainable square matrix resulting in substantial reductions in trainable parameters and peak GPU memory usage. LaMDA gradually freezes a second projection matrix (PMB) during the early fine45;tuning stages reducing the compute cost associated with weight updates to enhance parameter efficiency further. We also present an enhancement LaMDA++ incorporating a lite45;weight adaptive rank allocation for the LoRA path via normalized spectrum analysis of pre45;trained model weights. We evaluate LaMDA/LaMDA++ across various tasks including natural language understanding with the GLUE benchmark text summarization natural language generation and complex reasoning on different LLMs. Results show that LaMDA matches or surpasses the performance of existing alternatives while requiring up to 17.7x fewer parameter updates and up to 1.32x lower peak GPU memory usage during fine45;tuning. Code will be publicly available.
