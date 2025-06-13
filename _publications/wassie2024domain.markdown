---
layout: publication
title: 'Domain-specific Translation With Open-source Large Language Models: Resource-oriented Analysis'
authors: Aman Kassahun Wassie, Mahdi Molaei, Yasmin Moslem
conference: "Arxiv"
year: 2024
bibkey: wassie2024domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05862"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Distillation', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
In this work, we compare the domain-specific translation performance of open-source autoregressive decoder-only large language models (LLMs) with task-oriented machine translation (MT) models. Our experiments focus on the medical domain and cover four language directions with varied resource availability: English-to-French, English-to-Portuguese, English-to-Swahili, and Swahili-to-English. Despite recent advancements, LLMs demonstrate a significant quality gap in specialized translation compared to multilingual encoder-decoder MT models such as NLLB-200. Our results indicate that NLLB-200 3.3B outperforms all evaluated LLMs in the 7-8B parameter range across three out of the four language directions. While fine-tuning improves the performance of LLMs such as Mistral and Llama, these models still underperform compared to fine-tuned NLLB-200 3.3B models. Our findings highlight the ongoing need for specialized MT models to achieve high-quality domain-specific translation, especially in medium-resource and low-resource settings. Moreover, the superior performance of larger LLMs over their 8B variants suggests potential value in pre-training domain-specific medium-sized language models, employing targeted data selection and knowledge distillation approaches to enhance both quality and efficiency in specialized translation tasks.
