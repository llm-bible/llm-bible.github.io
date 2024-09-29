---
layout: publication
title: Modulora Finetuning 245;bit Llms On Consumer Gpus By Integrating With Modular Quantizers
authors: Yin Junjie, Dong Jiahao, Wang Yingheng, De Sa Christopher, Kuleshov Volodymyr
conference: "Arxiv"
year: 2023
bibkey: yin2023finetuning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.16119"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Quantization', 'RAG', 'Reinforcement Learning', 'Tools']
---
We propose a memory45;efficient finetuning algorithm for large language models (LLMs) that supports finetuning LLMs with 65B parameters in 2/3/445;bit precision on as little as one 24GB GPU. Our method modular low45;rank adaptation (ModuLoRA) integrates any user45;specified weight quantizer with finetuning via low45;rank adapters (LoRAs). Our approach relies on a simple quantization45;agnostic backward pass that adaptively materializes low45;precision LLM weights from a custom black45;box quantization module. This approach enables finetuning 245;bit and 345;bit LLMs for the first time 45;45; leveraging state45;of45;the45;art 245;bit QuIP35; quantization and 345;bit OPTQ quantization 45;45; outperforming finetuning that relies on less sophisticated 445;bit and 845;bit methods. In our experiments lplora~attains competitive performance on text classification natural language inference and instruction following tasks using significantly less memory than existing approaches and we also surpass the state45;of45;the45;art ROUGE score on a popular summarization task. We release lplora~together with a series of low45;precision models as part of llmtune a user45;friendly library for quantizing running and finetuning LLMs on consumer GPUs.
