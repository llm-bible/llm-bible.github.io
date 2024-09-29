---
layout: publication
title: Towards Democratizing Multilingual Large Language Models For Medicine Through A Two-Stage Instruction Fine-tuning Approach
authors: Zhou Meng, Parmar Surajsinh, Bhatti Anubhav
conference: "Arxiv"
year: 2024
bibkey: zhou2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.05732"}
  - {name: "Code", url: "https://github.com/SpassMed/Med-Llama3"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Open-source multilingual medical large language models (LLMs) have the potential to serve linguistically diverse populations across different regions. Adapting generic LLMs for healthcare often requires continual pretraining but this approach is computationally expensive and sometimes impractical. Instruction fine-tuning on a specific task may not always guarantee optimal performance due to the lack of broader domain knowledge that the model needs to understand and reason effectively in diverse scenarios. To address these challenges we introduce two multilingual instruction fine-tuning datasets MMed-IFT and MMed-IFT-MC containing over 200k high-quality medical samples in six languages. We propose a two-stage training paradigm the first stage injects general medical knowledge using MMed-IFT while the second stage fine-tunes task-specific multiple-choice questions with MMed-IFT-MC. Our method achieves competitive results on both English and multilingual benchmarks striking a balance between computational efficiency and performance. We plan to make our dataset and model weights public at url https://github.com/SpassMed/Med-Llama3 in the future.
