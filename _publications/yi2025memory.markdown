---
layout: publication
title: 'MINT: Memory-infused Prompt Tuning At Test-time For CLIP'
authors: Jiaming Yi, Ruirui Pan, Jishen Yang, Xiulong Yang
conference: "Arxiv"
year: 2025
bibkey: yi2025memory
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.03190'}
  - {name: "Code", url: 'https://github.com/Jamieyi2004/MINT'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Tools', 'Prompting', 'Multimodal Models', 'Reinforcement Learning']
---
Improving the generalization ability of Vision-Language Pre-trained Models (VLMs) under test-time data distribution shifts remains a critical challenge. The existing Test-Time Adaptation (TTA) methods fall short in fully leveraging the model's internal knowledge, particularly in dynamically adapting to complex and hierarchical visual semantic information. In this paper, we propose Memory-Infused Prompt Tuning (MINT), a novel framework to address this issue. Inspired by human associative memory theory, MINT introduces a Memory Prompt Bank (MPB), which stores learnable key-value prompt pairs that work as a memory of previously seen samples. During the test time, relevant prompt pairs in the MPB are retrieved by the hierarchical visual features of test images to dynamically assemble Associative Prompts. The associative prompts are then injected into the image encoder for fine-grained, customized visual contextual guidance. MINT also utilizes learnable text prompts. MINT thus enables rapid, precise VLM adaptation at test time by leveraging this MPB-acquired memory, without source data or retraining. The code is available at https://github.com/Jamieyi2004/MINT.
