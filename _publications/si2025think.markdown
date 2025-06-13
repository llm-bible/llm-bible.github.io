---
layout: publication
title: 'Think Before Refusal : Triggering Safety Reflection In Llms To Mitigate False Refusal Behavior'
authors: Shengyun Si, Xinpeng Wang, Guangyao Zhai, Nassir Navab, Barbara Plank
conference: "Arxiv"
year: 2025
bibkey: si2025think
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.17882'}
tags: ['Training Techniques', 'Fine-Tuning', 'Prompting', 'Responsible AI', 'Pretraining Methods']
---
Recent advancements in large language models (LLMs) have demonstrated that
fine-tuning and human alignment can render LLMs harmless. In practice, such
"harmlessness" behavior is mainly achieved by training models to reject harmful
requests, such as "Explain how to burn down my neighbor's house", where the
model appropriately declines to respond. However, this approach can
inadvertently result in false refusal, where models reject benign queries as
well, such as "Tell me how to kill a Python process". In this work, we
demonstrate that prompting safety reflection before generating a response can
mitigate false refusal behavior. Building on this finding, we introduce the
Think-Before-Refusal (TBR) schema and conduct safety-aware instruction
fine-tuning incorporating safety reflection. In an ablation study across 15
pre-trained models, we show that models fine-tuned with safety reflection
significantly reduce false refusal behavior while maintaining safety and
overall performance compared to those fine-tuned without safety reflection.
