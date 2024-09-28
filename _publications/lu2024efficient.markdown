---
layout: publication
title: Efficient Encoder-Decoder Transformer Decoding for Decomposable Tasks
authors: Lu Bo-ru, Haduong Nikita, Lin Chien-yu, Cheng Hao, Smith Noah A., Ostendorf Mari
conference: "Arxiv"
year: 2024
bibkey: lu2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13112"}
tags: ['ARXIV', 'Applications', 'GPT', 'Model Architecture', 'NLP', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Transformer-based NLP models are powerful but have high computational costs that limit deployment. Finetuned encoder-decoder models are popular in specialized domains and can outperform larger more generalized decoder-only models such as GPT-4. We introduce a new configuration for encoder-decoder models that improves efficiency on structured output and decomposable tasks where multiple outputs are required for a single shared input. Our method prompt-in-decoder (PiD) encodes the input once and decodes the output in parallel boosting both training and inference efficiency by avoiding duplicate input encoding and increasing the operational intensity (ratio of numbers of arithmetic operation to memory access) of decoding process by sharing the input key-value cache. We achieve computation reduction that roughly scales with the number of subtasks gaining up to 4.6x speed-up over state-of-the-art models for dialogue state tracking summarization and question-answering tasks with comparable or better performance.
