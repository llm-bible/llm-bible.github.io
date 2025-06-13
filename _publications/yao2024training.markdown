---
layout: publication
title: 'Training Ultra Long Context Language Model With Fully Pipelined Distributed Transformer'
authors: Jinghan Yao, Sam Ade Jacobs, Masahiro Tanaka, Olatunji Ruwase, Hari Subramoni, Dhabaleswar K. Panda
conference: "Arxiv"
year: 2024
bibkey: yao2024training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.16978'}
tags: ['Language Modeling', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'GPT', 'Model Architecture', 'Applications', 'Pretraining Methods']
---
Large Language Models (LLMs) with long context capabilities are integral to complex tasks in natural language processing and computational biology, such as text generation and protein sequence analysis. However, training LLMs directly on extremely long contexts demands considerable GPU resources and increased memory, leading to higher costs and greater complexity. Alternative approaches that introduce long context capabilities via downstream finetuning or adaptations impose significant design limitations. In this paper, we propose Fully Pipelined Distributed Transformer (FPDT) for efficiently training long-context LLMs with extreme hardware efficiency. For GPT and Llama models, we achieve a 16x increase in sequence length that can be trained on the same hardware compared to current state-of-the-art solutions. With our dedicated sequence chunk pipeline design, we can now train 8B LLM with 2 million sequence length on only 4 GPUs, while also maintaining over 55% of MFU. Our proposed FPDT is agnostic to existing training techniques and is proven to work efficiently across different LLM models.
