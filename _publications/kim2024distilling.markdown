---
layout: publication
title: Promptkd Distilling Student45;friendly Knowledge For Generative Language Models Via Prompt Tuning
authors: Kim Gyeongman, Jang Doohyuk, Yang Eunho
conference: "Arxiv"
year: 2024
bibkey: kim2024distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12842"}
tags: ['Distillation', 'Efficiency And Optimization', 'Ethics And Bias', 'Prompting', 'Quantization', 'Training Techniques']
---
Recent advancements in large language models (LLMs) have raised concerns about inference costs increasing the need for research into model compression. While knowledge distillation (KD) is a prominent method for this research on KD for generative language models like LLMs is relatively sparse and the approach of distilling student45;friendly knowledge which has shown promising performance in KD for classification models remains unexplored in generative language models. To explore this approach we propose PromptKD a simple yet effective method that utilizes prompt tuning 45; for the first time in KD 45; to enable generative language models to transfer student45;friendly knowledge. Unlike previous works in classification that require fine45;tuning the entire teacher model for extracting student45;friendly knowledge PromptKD achieves similar effects by adding a small number of prompt tokens and tuning only the prompt with student guidance. Extensive experiments on instruction45;following datasets show that PromptKD achieves state45;of45;the45;art performance while adding only 0.000737; of the teachers parameters as prompts. Further analysis suggests that distilling student45;friendly knowledge alleviates exposure bias effectively throughout the entire training process leading to performance enhancements.
