---
layout: publication
title: 'Moqagpt : Zero-shot Multi-modal Open-domain Question Answering With Large Language Model'
authors: Zhang Le, Wu Yihong, Mo Fengran, Nie Jian-yun, Agrawal Aishwarya
conference: "Arxiv"
year: 2023
bibkey: zhang2023moqagpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13265"}
  - {name: "Code", url: "https://github.com/lezhang7/MOQAGPT"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Tools']
---
"Multi-modal open-domain question answering typically requires evidence retrieval from databases across diverse modalities, such as images, tables, passages, etc. Even Large Language Models (LLMs) like GPT-4 fall short in this task. To enable LLMs to tackle the task in a zero-shot manner, we introduce MoqaGPT, a straightforward and flexible framework. Using a divide-and-conquer strategy that bypasses intricate multi-modality ranking, our framework can accommodate new modalities and seamlessly transition to new models for the task. Built upon LLMs, MoqaGPT retrieves and extracts answers from each modality separately, then fuses this multi-modal information using LLMs to produce a final answer. Our methodology boosts performance on the MMCoQA dataset, improving F1 by +37.91 points and EM by +34.07 points over the supervised baseline. On the MultiModalQA dataset, MoqaGPT surpasses the zero-shot baseline, improving F1 by 9.5 points and EM by 10.1 points, and significantly closes the gap with supervised methods. Our codebase is available at https://github.com/lezhang7/MOQAGPT."
