---
layout: publication
title: Sparq Attention: Bandwidth-efficient LLM Inference
authors: Ribar Luka, Chelombiev Ivan, Hudlass-galley Luke, Blake Charlie, Luschi Carlo, Orr Douglas
conference: "Arxiv"
year: 2023
bibkey: ribar2023sparq
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04985"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'TACL', 'Training Techniques']
---
The computational difficulties of large language model (LLM) inference remain a significant obstacle to their widespread deployment. The need for many applications to support long input sequences and process them in large batches typically causes token-generation to be bottlenecked by data transfer. For this reason we introduce SparQ Attention a technique for increasing the inference throughput of LLMs by utilising memory bandwidth more efficiently within the attention layers through selective fetching of the cached history. Our proposed technique can be applied directly to off-the-shelf LLMs during inference without requiring any modification to the pre-training setup or additional fine-tuning. We show that SparQ Attention brings up to 8x savings in attention data transfers without substantial drops in accuracy by evaluating Llama 2 and 3 Mistral Gemma and Pythia models on a wide range of downstream tasks.
