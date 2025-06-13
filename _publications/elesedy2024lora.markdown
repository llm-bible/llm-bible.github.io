---
layout: publication
title: 'Lora-guard: Parameter-efficient Guardrail Adaptation For Content Moderation Of Large Language Models'
authors: Hayder Elesedy, Pedro M. Esperança, Silviu Vlad Oprea, Mete Ozay
conference: "Arxiv"
year: 2024
bibkey: elesedy2024lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02987"}
tags: ['Fine-Tuning', 'Responsible AI', 'Applications']
---
Guardrails have emerged as an alternative to safety alignment for content
moderation of large language models (LLMs). Existing model-based guardrails
have not been designed for resource-constrained computational portable devices,
such as mobile phones, more and more of which are running LLM-based
applications locally. We introduce LoRA-Guard, a parameter-efficient guardrail
adaptation method that relies on knowledge sharing between LLMs and guardrail
models. LoRA-Guard extracts language features from the LLMs and adapts them for
the content moderation task using low-rank adapters, while a dual-path design
prevents any performance degradation on the generative task. We show that
LoRA-Guard outperforms existing approaches with 100-1000x lower parameter
overhead while maintaining accuracy, enabling on-device content moderation.
