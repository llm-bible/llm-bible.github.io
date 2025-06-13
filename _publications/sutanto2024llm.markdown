---
layout: publication
title: 'LLM Distillation For Efficient Few-shot Multiple Choice Question Answering'
authors: Patrick Sutanto, Joan Santoso, Esther Irawati Setiawan, Aji Prasetya Wibawa
conference: "Arxiv"
year: 2024
bibkey: sutanto2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.09807"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Few-Shot', 'Reinforcement Learning', 'RAG', 'Distillation', 'BERT', 'Applications']
---
Multiple Choice Question Answering (MCQA) is an important problem with
numerous real-world applications, such as medicine, law, and education. The
high cost of building MCQA datasets makes few-shot learning pivotal in this
domain. While Large Language Models (LLMs) can enable few-shot learning, their
direct application in real-world scenarios is often hindered by their high
computational cost. To address this challenge, we propose a simple yet
effective approach that uses LLMs for data generation and scoring. Our approach
utilizes LLMs to create MCQA data which contains questions and choices, and to
assign probability scores to the generated choices. We then use the generated
data and LLM-assigned scores to finetune a smaller and more efficient
encoder-only model, DeBERTa-v3-base by leveraging distillation loss. Extensive
experiments on the Massive Multitask Language Understanding (MMLU) benchmark
demonstrate that our method improves accuracy from 28.9% to 39.3%, representing
a gain of over 10% compared to a baseline finetuned directly on 5-shot
examples. This shows the effectiveness of LLM-driven data generation and
knowledge distillation for few-shot MCQA.
