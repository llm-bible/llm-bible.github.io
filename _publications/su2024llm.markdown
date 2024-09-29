---
layout: publication
title: Llm45;barber Block45;aware Rebuilder For Sparsity Mask In One45;shot For Large Language Models
authors: Su Yupeng, Guan Ziyi, Liu Xiaoqun, Jin Tianlai, Wu Dongkuan, Chesi Graziano, Wong Ngai, Yu Hao
conference: "Arxiv"
year: 2024
bibkey: su2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10631"}
  - {name: "Code", url: "https://github.com/YupengSu/LLM&#45;Barber"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pruning', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have grown significantly in scale leading to a critical need for efficient model pruning techniques. Existing post45;training pruning techniques primarily focus on measuring weight importance on converged dense models to determine salient weights to retain. However they often overlook the changes in weight importance during the pruning process which can lead to performance degradation in the pruned models. To address this issue we present LLM45;Barber (Block45;Aware Rebuilder for Sparsity Mask in One45;Shot) a novel one45;shot pruning framework that rebuilds the sparsity mask of pruned models without any retraining or weight reconstruction. LLM45;Barber incorporates block45;aware error optimization across Self45;Attention and MLP blocks ensuring global performance optimization. Inspired by the recent discovery of prominent outliers in LLMs LLM45;Barber introduces an innovative pruning metric that identifies weight importance using weights multiplied by gradients. Our experiments show that LLM45;Barber can efficiently prune models like LLaMA and OPT families with 7B to 13B parameters on a single A100 GPU in just 30 minutes achieving state45;of45;the45;art results in both perplexity and zero45;shot performance across various language benchmarks. Code is available at https://github.com/YupengSu/LLM&#45;Barber.
