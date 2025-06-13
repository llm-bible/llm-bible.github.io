---
layout: publication
title: 'Parallelcomp: Parallel Long-context Compressor For Length Extrapolation'
authors: Jing Xiong, Jianghan Shen, Chuanyang Zheng, Zhongwei Wan, Chenyang Zhao, Chiwun Yang, Fanghua Ye, Hongxia Yang, Lingpeng Kong, Ngai Wong
conference: "Arxiv"
year: 2025
bibkey: xiong2025parallel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14317"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'GPT', 'Ethics and Bias', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Efficiently handling long contexts is crucial for large language models
(LLMs). While rotary position embeddings (RoPEs) enhance length generalization,
effective length extrapolation remains challenging and often requires costly
fine-tuning. In contrast, recent training-free approaches suffer from the
attention sink phenomenon, leading to severe performance degradation. In this
paper, we introduce ParallelComp, a novel training-free method for long-context
extrapolation that extends LLMs' context length from 4K to 128K while
maintaining high throughput and preserving perplexity, and integrates
seamlessly with Flash Attention. Our analysis offers new insights into
attention biases in parallel attention mechanisms and provides practical
solutions to tackle these challenges. To mitigate the attention sink issue, we
propose an attention calibration strategy that reduces biases, ensuring more
stable long-range attention. Additionally, we introduce a chunk eviction
strategy to efficiently manage ultra-long contexts on a single A100 80GB GPU.
To further enhance efficiency, we propose a parallel KV cache eviction
technique, which improves chunk throughput by 1.76x, thereby achieving a 23.50x
acceleration in the prefilling stage with negligible performance loss due to
attention calibration. Furthermore, ParallelComp achieves 91.17% of GPT-4's
performance on long-context tasks using an 8B model trained on 8K-length
context, outperforming powerful closed-source models such as Claude-2 and
Kimi-Chat.
