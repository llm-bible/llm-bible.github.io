---
layout: publication
title: 'Llm-barber: Block-aware Rebuilder For Sparsity Mask In One-shot For Large Language Models'
authors: Su Yupeng, Guan Ziyi, Liu Xiaoqun, Jin Tianlai, Wu Dongkuan, Chesi Graziano, Wong Ngai, Yu Hao
conference: "Arxiv"
year: 2024
bibkey: su2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10631"}
  - {name: "Code", url: "https://github.com/YupengSu/LLM-Barber"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pruning', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Large language models (LLMs) have grown significantly in scale, leading to a
critical need for efficient model pruning techniques. Existing post-training
pruning techniques primarily focus on measuring weight importance on converged
dense models to determine salient weights to retain. However, they often
overlook the changes in weight importance during the pruning process, which can
lead to performance degradation in the pruned models. To address this issue, we
present LLM-Barber (Block-Aware Rebuilder for Sparsity Mask in One-Shot), a
novel one-shot pruning framework that rebuilds the sparsity mask of pruned
models without any retraining or weight reconstruction. LLM-Barber incorporates
block-aware error optimization across Self-Attention and MLP blocks, ensuring
global performance optimization. Inspired by the recent discovery of prominent
outliers in LLMs, LLM-Barber introduces an innovative pruning metric that
identifies weight importance using weights multiplied by gradients. Our
experiments show that LLM-Barber can efficiently prune models like LLaMA and
OPT families with 7B to 13B parameters on a single A100 GPU in just 30 minutes,
achieving state-of-the-art results in both perplexity and zero-shot performance
across various language benchmarks. Code is available at
https://github.com/YupengSu/LLM-Barber.
