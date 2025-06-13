---
layout: publication
title: 'Contrastive Prompting Enhances Sentence Embeddings In Llms Through Inference-time Steering'
authors: Zifeng Cheng, Zhonghui Wang, Yuchen Fu, Zhiwei Jiang, Yafeng Yin, Cong Wang, Qing Gu
conference: "Arxiv"
year: 2025
bibkey: cheng2025contrastive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.12831'}
  - {name: "Code", url: 'https://github.com/zifengcheng/CP'}
tags: ['Has Code', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Extracting sentence embeddings from large language models (LLMs) is a practical direction, as it requires neither additional data nor fine-tuning. Previous studies usually focus on prompt engineering to guide LLMs to encode the core semantic information of the sentence into the embedding of the last token. However, the last token in these methods still encodes an excess of non-essential information, such as stop words, limiting its encoding capacity. To this end, we propose a Contrastive Prompting (CP) method that introduces an extra auxiliary prompt to elicit better sentence embedding. By contrasting with the auxiliary prompt, CP can steer existing prompts to encode the core semantics of the sentence, rather than non-essential information. CP is a plug-and-play inference-time intervention method that can be combined with various prompt-based methods. Extensive experiments on Semantic Textual Similarity (STS) tasks and downstream classification tasks demonstrate that our method can improve the performance of existing prompt-based methods across different LLMs. Our code will be released at https://github.com/zifengcheng/CP.
