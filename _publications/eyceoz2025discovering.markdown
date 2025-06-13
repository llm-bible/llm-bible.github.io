---
layout: publication
title: 'Hopscotch: Discovering And Skipping Redundancies In Language Models'
authors: Mustafa Eyceoz, Nikhil Shivakumar Nayak, Hao Wang, Ligong Han, Akash Srivastava
conference: "Arxiv"
year: 2025
bibkey: eyceoz2025discovering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03303"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Quantization']
---
Modern causal language models stack many attention blocks to improve performance, but not all blocks are necessary for every task. We propose Hopscotch, a simple yet effective method that identifies and skips attention blocks with least contributions to a task and adapts to preserve output quality. Hopscotch jointly optimizes which blocks to skip and how to scale the outputs of the remaining layers. By introducing lightweight, trainable scaling parameters to attention and MLP blocks, it mitigates distribution shifts in hidden states caused by removing attention blocks. Hopscotch does not modify model weights or require access to pretraining or instruction-tuning data, and is compatible with existing model compression techniques. When applied to \\(\texttt\{Llama-3.1-8B\}\\) and \\(\texttt\{Qwen2.5-7B\}\\), Hopscotch achieves less than a 2% drop in performance even after skipping four attention blocks.
