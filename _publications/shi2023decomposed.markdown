---
layout: publication
title: Dept Decomposed Prompt Tuning For Parameter45;efficient Fine45;tuning
authors: Shi Zhengxiang, Lipani Aldo
conference: "Arxiv"
year: 2023
bibkey: shi2023decomposed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.05173"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Prompt tuning (PT) where a small amount of trainable soft (continuous) prompt vectors is affixed to the input of language models (LM) has shown promising results across various tasks and models for parameter45;efficient fine45;tuning (PEFT). PT stands out from other PEFT approaches because it maintains competitive performance with fewer trainable parameters and does not drastically scale up its parameters as the model size expands. However PT introduces additional soft prompt tokens leading to longer input sequences which significantly impacts training and inference time and memory usage due to the Transformers quadratic complexity. Particularly concerning for Large Language Models (LLMs) that face heavy daily querying. To address this issue we propose Decomposed Prompt Tuning (DePT) which decomposes the soft prompt into a shorter soft prompt and a pair of low45;rank matrices that are then optimised with two different learning rates. This allows DePT to achieve better performance while saving substantial memory and time costs compared to vanilla PT and its variants without changing trainable parameter sizes. Through extensive experiments on 23 natural language processing (NLP) and vision45;language (VL) tasks we demonstrate that DePT outperforms state45;of45;the45;art PEFT approaches including the full fine45;tuning baseline in some scenarios. Additionally we empirically show that DEPT grows more efficient as the model size increases. Our further study reveals that DePT integrates seamlessly with parameter45;efficient transfer learning in the few45;shot learning setting and highlights its adaptability to various model architectures and sizes.
