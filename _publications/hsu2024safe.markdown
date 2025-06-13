---
layout: publication
title: 'Safe Lora: The Silver Lining Of Reducing Safety Risks When Fine-tuning Large Language Models'
authors: Chia-yi Hsu, Yu-lin Tsai, Chih-hsun Lin, Pin-yu Chen, Chia-mu Yu, Chun-ying Huang
conference: "Arxiv"
year: 2024
bibkey: hsu2024safe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16833"}
  - {name: "Code", url: "https://github.com/IBM/SafeLoRA"}
tags: ['Responsible AI', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
While large language models (LLMs) such as Llama-2 or GPT-4 have shown
impressive zero-shot performance, fine-tuning is still necessary to enhance
their performance for customized datasets, domain-specific tasks, or other
private needs. However, fine-tuning all parameters of LLMs requires significant
hardware resources, which can be impractical for typical users. Therefore,
parameter-efficient fine-tuning such as LoRA have emerged, allowing users to
fine-tune LLMs without the need for considerable computing resources, with
little performance degradation compared to fine-tuning all parameters.
Unfortunately, recent studies indicate that fine-tuning can increase the risk
to the safety of LLMs, even when data does not contain malicious content. To
address this challenge, we propose Safe LoRA, a simple one-liner patch to the
original LoRA implementation by introducing the projection of LoRA weights from
selected layers to the safety-aligned subspace, effectively reducing the safety
risks in LLM fine-tuning while maintaining utility. It is worth noting that
Safe LoRA is a training-free and data-free approach, as it only requires the
knowledge of the weights from the base and aligned LLMs. Our extensive
experiments demonstrate that when fine-tuning on purely malicious data, Safe
LoRA retains similar safety performance as the original aligned model.
Moreover, when the fine-tuning dataset contains a mixture of both benign and
malicious data, Safe LoRA mitigates the negative effect made by malicious data
while preserving performance on downstream tasks. Our codes are available at
\url\{https://github.com/IBM/SafeLoRA\}.
