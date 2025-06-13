---
layout: publication
title: 'TOAST: Transfer Learning Via Attention Steering'
authors: Baifeng Shi, Siyu Gai, Trevor Darrell, Xin Wang
conference: "Arxiv"
year: 2023
bibkey: shi2023transfer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.15542'}
  - {name: "Code", url: 'https://github.com/bfshi/TOAST'}
tags: ['Attention Mechanism', 'Has Code', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Transfer learning involves adapting a pre-trained model to novel downstream
tasks. However, we observe that current transfer learning methods often fail to
focus on task-relevant features. In this work, we explore refocusing model
attention for transfer learning. We introduce Top-Down Attention Steering
(TOAST), a novel transfer learning algorithm that keeps the pre-trained
backbone frozen, selects task-relevant features in the output, and feeds those
features back to the model to steer the attention to the task-specific
features. By refocusing the attention only, TOAST achieves state-of-the-art
results on a number of transfer learning benchmarks, while having a small
number of tunable parameters. Compared to fully fine-tuning, LoRA, and prompt
tuning, TOAST substantially improves performance across a range of fine-grained
visual classification datasets (e.g., 81.1% -> 86.2% on FGVC). TOAST also
outperforms the fully fine-tuned Alpaca and Vicuna models on
instruction-following language generation. Code is available at
https://github.com/bfshi/TOAST.
