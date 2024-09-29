---
layout: publication
title: "Bridging The Language Gap: Enhancing Multilingual Prompt-based Code Generation In Llms Via Zero-shot Cross-lingual Transfer"
authors: Li Mingda, Mishra Abhijit, Mujumdar Utkarsh
conference: "Arxiv"
year: 2024
bibkey: li2024bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09701"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
The use of Large Language Models (LLMs) for program code generation has gained substantial attention but their biases and limitations with non-English prompts challenge global inclusivity. This paper investigates the complexities of multilingual prompt-based code generation. Our evaluations of LLMs including CodeLLaMa and CodeGemma reveal significant disparities in code quality for non-English prompts; we also demonstrate the inadequacy of simple approaches like prompt translation bootstrapped data augmentation and fine-tuning. To address this we propose a zero-shot cross-lingual approach using a neural projection technique integrating a cross-lingual encoder like LASER artetxe2019massively to map multilingual embeddings from it into the LLMs token space. This method requires training only on English data and scales effectively to other languages. Results on a translated and quality-checked MBPP dataset show substantial improvements in code quality. This research promotes a more inclusive code generation landscape by empowering LLMs with multilingual capabilities to support the diverse linguistic spectrum in programming.
