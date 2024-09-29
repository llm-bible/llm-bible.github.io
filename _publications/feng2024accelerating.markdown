---
layout: publication
title: Optimus Accelerating Large45;scale Multi45;modal LLM Training By Bubble Exploitation
authors: Feng Weiqi, Chen Yangrui, Wang Shaoyu, Peng Yanghua, Lin Haibin, Yu Minlan
conference: "Arxiv"
year: 2024
bibkey: feng2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03505"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Multimodal Models', 'Training Techniques']
---
Multimodal large language models (MLLMs) have extended the success of large language models (LLMs) to multiple data types such as image text and audio achieving significant performance in various domains including multimodal translation visual question answering and content generation. Nonetheless existing systems are inefficient to train MLLMs due to substantial GPU bubbles caused by the heterogeneous modality models and complex data dependencies in 3D parallelism. This paper proposes Optimus a distributed MLLM training system that reduces end45;to45;end MLLM training time. Optimus is based on our principled analysis that scheduling the encoder computation within the LLM bubbles can reduce bubbles in MLLM training. To make scheduling encoder computation possible for all GPUs Optimus searches the separate parallel plans for encoder and LLM and adopts a bubble scheduling algorithm to enable exploiting LLM bubbles without breaking the original data dependencies in the MLLM model architecture. We further decompose encoder layer computation into a series of kernels and analyze the common bubble pattern of 3D parallelism to carefully optimize the sub45;millisecond bubble scheduling minimizing the overall training time. Our experiments in a production cluster show that Optimus accelerates MLLM training by 20.537;45;21.337; with ViT45;22B and GPT45;175B model over 3072 GPUs compared to baselines.
