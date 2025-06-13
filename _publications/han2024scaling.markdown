---
layout: publication
title: 'Infinity: Scaling Bitwise Autoregressive Modeling For High-resolution Image Synthesis'
authors: Jian Han, Jinlai Liu, Yi Jiang, Bin Yan, Yuqi Zhang, Zehuan Yuan, Bingyue Peng, Xiaobing Liu
conference: "Arxiv"
year: 2024
bibkey: han2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04431"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Merging', 'Pretraining Methods']
---
We present Infinity, a Bitwise Visual AutoRegressive Modeling capable of
generating high-resolution, photorealistic images following language
instruction. Infinity redefines visual autoregressive model under a bitwise
token prediction framework with an infinite-vocabulary tokenizer & classifier
and bitwise self-correction mechanism, remarkably improving the generation
capacity and details. By theoretically scaling the tokenizer vocabulary size to
infinity and concurrently scaling the transformer size, our method
significantly unleashes powerful scaling capabilities compared to vanilla VAR.
Infinity sets a new record for autoregressive text-to-image models,
outperforming top-tier diffusion models like SD3-Medium and SDXL. Notably,
Infinity surpasses SD3-Medium by improving the GenEval benchmark score from
0.62 to 0.73 and the ImageReward benchmark score from 0.87 to 0.96, achieving a
win rate of 66%. Without extra optimization, Infinity generates a high-quality
1024x1024 image in 0.8 seconds, making it 2.6x faster than SD3-Medium and
establishing it as the fastest text-to-image model. Models and codes will be
released to promote further exploration of Infinity for visual generation and
unified tokenizer modeling.
