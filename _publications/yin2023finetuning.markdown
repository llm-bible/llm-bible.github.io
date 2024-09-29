---
layout: publication
title: Modulora Finetuning 2-bit Llms On Consumer Gpus By Integrating With Modular Quantizers
authors: Yin Junjie, Dong Jiahao, Wang Yingheng, De Sa Christopher, Kuleshov Volodymyr
conference: "Arxiv"
year: 2023
bibkey: yin2023finetuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16119"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Quantization', 'RAG', 'Reinforcement Learning', 'Tools']
---
We propose a memory-efficient finetuning algorithm for large language models (LLMs) that supports finetuning LLMs with 65B parameters in 2/3/4-bit precision on as little as one 24GB GPU. Our method modular low-rank adaptation (ModuLoRA) integrates any user-specified weight quantizer with finetuning via low-rank adapters (LoRAs). Our approach relies on a simple quantization-agnostic backward pass that adaptively materializes low-precision LLM weights from a custom black-box quantization module. This approach enables finetuning 2-bit and 3-bit LLMs for the first time -- leveraging state-of-the-art 2-bit QuIP35; quantization and 3-bit OPTQ quantization -- outperforming finetuning that relies on less sophisticated 4-bit and 8-bit methods. In our experiments (lplora)~attains competitive performance on text classification natural language inference and instruction following tasks using significantly less memory than existing approaches and we also surpass the state-of-the-art ROUGE score on a popular summarization task. We release (lplora)~together with a series of low-precision models as part of (llmtune) a user-friendly library for quantizing running and finetuning LLMs on consumer GPUs.
