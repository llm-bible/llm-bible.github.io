---
layout: publication
title: Efficient Encoder45;decoder Transformer Decoding For Decomposable Tasks
authors: Lu Bo-ru, Haduong Nikita, Lin Chien-yu, Cheng Hao, Smith Noah A., Ostendorf Mari
conference: "Arxiv"
year: 2024
bibkey: lu2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13112"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Transformer45;based NLP models are powerful but have high computational costs that limit deployment. Finetuned encoder45;decoder models are popular in specialized domains and can outperform larger more generalized decoder45;only models such as GPT45;4. We introduce a new configuration for encoder45;decoder models that improves efficiency on structured output and decomposable tasks where multiple outputs are required for a single shared input. Our method prompt45;in45;decoder (PiD) encodes the input once and decodes the output in parallel boosting both training and inference efficiency by avoiding duplicate input encoding and increasing the operational intensity (ratio of numbers of arithmetic operation to memory access) of decoding process by sharing the input key45;value cache. We achieve computation reduction that roughly scales with the number of subtasks gaining up to 4.6x speed45;up over state45;of45;the45;art models for dialogue state tracking summarization and question45;answering tasks with comparable or better performance.
