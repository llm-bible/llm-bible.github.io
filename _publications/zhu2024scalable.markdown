---
layout: publication
title: 'Scalable Matmul-free Language Modeling'
authors: Zhu Rui-jie, Zhang Yu, Sifferman Ethan, Sheaves Tyler, Wang Yiqiao, Richmond Dustin, Zhou Peng, Eshraghian Jason K.
conference: "Arxiv"
year: 2024
bibkey: zhu2024scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02528"}
  - {name: "Code", url: "https://github.com/ridgerchu/matmulfreellm"}
tags: ['Efficiency And Optimization', 'Has Code', 'Language Modeling', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques', 'Transformer']
---
Matrix multiplication (MatMul) typically dominates the overall computational cost of large language models (LLMs). This cost only grows as LLMs scale to larger embedding dimensions and context lengths. In this work we show that MatMul operations can be completely eliminated from LLMs while maintaining strong performance at billion-parameter scales. Our experiments show that our proposed MatMul-free models achieve performance on-par with state-of-the-art Transformers that require far more memory during inference at a scale up to at least 2.7B parameters. We investigate the scaling laws and find that the performance gap between our MatMul-free models and full precision Transformers narrows as the model size increases. We also provide a GPU-efficient implementation of this model which reduces memory usage by up to 6137; over an unoptimized baseline during training. By utilizing an optimized kernel during inference our models memory consumption can be reduced by more than 10x compared to unoptimized models. To properly quantify the efficiency of our architecture we build a custom hardware solution on an FPGA which exploits lightweight operations beyond what GPUs are capable of. We processed billion-parameter scale models at 13W beyond human readable throughput moving LLMs closer to brain-like efficiency. This work not only shows how far LLMs can be stripped back while still performing effectively but also points at the types of operations future accelerators should be optimized for in processing the next generation of lightweight LLMs. Our code implementation is available at https://github.com/ridgerchu/matmulfreellm."
