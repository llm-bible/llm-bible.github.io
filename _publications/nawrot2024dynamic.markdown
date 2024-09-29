---
layout: publication
title: Dynamic Memory Compression Retrofitting Llms For Accelerated Inference
authors: Nawrot Piotr, Łańcucki Adrian, Chochowski Marcin, Tarjan David, Ponti Edoardo M.
conference: "Proceedings of the"
year: 2024
bibkey: nawrot2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09636"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Transformers have emerged as the backbone of large language models (LLMs). However generation remains inefficient due to the need to store in memory a cache of key45;value representations for past tokens whose size scales linearly with the input sequence length and batch size. As a solution we propose Dynamic Memory Compression (DMC) a method for online key45;value cache compression at inference time. Most importantly the model learns to apply different compression ratios in different heads and layers. We retrofit pre45;trained LLMs such as Llama 2 (7B 13B and 70B) into DMC Transformers achieving up to 7x throughput increase during auto45;regressive inference on an NVIDIA H100 GPU. DMC is applied via continued pre45;training on a negligible percentage of the original data without adding any extra parameters. DMC preserves the original downstream performance with up to 4x cache compression outperforming up45;trained grouped45;query attention (GQA) and key45;value eviction policies (H95;2O TOVA). GQA and DMC can be even combined to obtain compounded gains. Hence DMC can serve as a drop45;in replacement for KV caching in existing LLMs to fit longer contexts and larger batches within any given memory budget.
