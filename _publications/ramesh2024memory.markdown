---
layout: publication
title: 'Blockllm: Memory-efficient Adaptation Of Llms By Selecting And Optimizing The Right Coordinate Blocks'
authors: Amrutha Varshini Ramesh, Vignesh Ganapathiraman, Issam H. Laradji, Mark Schmidt
conference: "Arxiv"
year: 2024
bibkey: ramesh2024memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17296"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Training large language models (LLMs) for pretraining or adapting to new
tasks and domains has become increasingly critical as their applications
expand. However, as the model and the data sizes grow, the training process
presents significant memory challenges, often requiring a prohibitive amount of
GPU memory that may not be readily available. Existing methods such as low-rank
adaptation (LoRA) add trainable low-rank matrix factorizations, altering the
training dynamics and limiting the model's parameter search to a low-rank
subspace. GaLore, a more recent method, employs Gradient Low-Rank Projection to
reduce the memory footprint, in the full parameter training setting. However
GaLore can only be applied to a subset of the LLM layers that satisfy the
"reversibility" property, thus limiting their applicability. In response to
these challenges, we introduce BlockLLM, an approach inspired by block
coordinate descent. Our method carefully selects and updates a very small
subset of the trainable parameters without altering any part of its
architecture and training procedure. BlockLLM achieves state-of-the-art
performance in both finetuning and pretraining tasks, while reducing the memory
footprint of the underlying optimization process. Our experiments demonstrate
that fine-tuning with only less than 5% of the parameters, BlockLLM achieves
state-of-the-art perplexity scores on the GLUE benchmarks. On Llama model
pretrained on C4 dataset, BlockLLM is able to train with significantly less
memory than the state-of-the-art, while still maintaining competitive
performance.
