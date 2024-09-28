---
layout: publication
title: Compress Then Prompt Improving Accuracy-Efficiency Trade-off of LLM Inference with Transferable Prompt
authors: Xu Zhaozhuo, Liu Zirui, Chen Beidi, Tang Yuxin, Wang Jue, Zhou Kaixiong, Hu Xia, Shrivastava Anshumali
conference: "Arxiv"
year: 2023
bibkey: xu2023compress
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11186"}
tags: ['ARXIV', 'Distillation', 'Efficiency And Optimization', 'LLM', 'Prompt', 'Quantization']
---
While the numerous parameters in Large Language Models (LLMs) contribute to their superior performance this massive scale makes them inefficient and memory-hungry. Thus they are hard to deploy on commodity hardware such as one single GPU. Given the memory and power constraints of such devices model compression methods are widely employed to reduce both the model size and inference latency which essentially trades off model quality in return for improved efficiency. Thus optimizing this accuracy-efficiency trade-off is crucial for the LLM deployment on commodity hardware. In this paper we introduce a new perspective to optimize this trade-off by prompting compressed models. Specifically we first observe that for certain questions the generation quality of a compressed LLM can be significantly improved by adding carefully designed hard prompts though this isnt the case for all questions. Based on this observation we propose a soft prompt learning method where we expose the compressed model to the prompt learning process aiming to enhance the performance of prompts. Our experimental analysis suggests our soft prompt strategy greatly improves the performance of the 8x compressed LLaMA-7B model (with a joint 4-bit quantization and 50 weight pruning compression) allowing them to match their uncompressed counterparts on popular benchmarks. Also we demonstrate that these learned prompts can be transferred across various datasets tasks and compression levels. Hence with this transferability we can stitch the soft prompt to a newly compressed model to improve the test-time accuracy in an in-situ way.
