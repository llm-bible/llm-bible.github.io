---
layout: publication
title: 'Emergence And Effectiveness Of Task Vectors In In-context Learning: An Encoder Decoder Perspective'
authors: Seungwook Han, Jinyeop Song, Jeff Gore, Pulkit Agrawal
conference: "Arxiv"
year: 2024
bibkey: han2024emergence
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12276'}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Training Techniques', 'Tools', 'GPT', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
Autoregressive transformers exhibit adaptive learning through in-context learning (ICL), which begs the question of how. Prior works have shown that transformers represent the ICL tasks as vectors in their representations. In this paper, we leverage the encoding-decoding framework to study how transformers form task vectors during pretraining and how their task encoding quality predicts ICL task performance. On synthetic ICL tasks, we analyze the training dynamics of a small transformer and report the coupled emergence of task encoding and decoding. As the model learns to encode different latent tasks (e.g., "Finding the first noun in a sentence.") into distinct, separable representations, it concurrently builds conditional decoding algorithms and improves its ICL performance. We validate this phenomenon across pretrained models of varying scales (Gemma-2 2B/9B/27B, Llama-3.1 8B/70B) and over the course of pretraining in OLMo-7B. Further, we demonstrate that the quality of task encoding inferred from representations predicts ICL performance, and that, surprisingly, finetuning the earlier layers can improve the task encoding and performance more than finetuning the latter layers. Our empirical insights shed light into better understanding the success and failure modes of large language models via their representations.
