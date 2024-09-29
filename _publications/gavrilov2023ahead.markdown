---
layout: publication
title: 'Ahead-of-time P-tuning'
authors: Gavrilov Daniil, Balagansky Nikita
conference: "Arxiv"
year: 2023
bibkey: gavrilov2023ahead
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.10835"}
tags: ['Applications', 'BERT', 'Ethics And Bias', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
In this paper we propose Ahead-of-Time (AoT) P-Tuning a novel parameter-efficient fine-tuning method for pre-trained Language Models (LMs) that adds input-dependent bias before each Transformer layer. We evaluate AoT P-Tuning on GLUE and SuperGLUE benchmarking datasets using RoBERTa and DeBERTa models showing that it outperforms BitFit and is comparable or better than other baseline methods for efficient fine-tuning. Additionally we assess the inference overhead of AoT P-Tuning and demonstrate that it introduces negligible overhead compared to established baseline methods. Our method enables multi-task inference with a single backbone LM making it a practical solution for real-world applications.
