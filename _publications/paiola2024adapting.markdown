---
layout: publication
title: 'Adapting Llms For The Medical Domain In Portuguese: A Study On Fine-tuning And Model Evaluation'
authors: Pedro Henrique Paiola, Gabriel Lino Garcia, João Renato Ribeiro Manesco, Mateus Roder, Douglas Rodrigues, João Paulo Papa
conference: "Arxiv"
year: 2024
bibkey: paiola2024adapting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.00163'}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Responsible AI', 'Pretraining Methods']
---
This study evaluates the performance of large language models (LLMs) as
medical agents in Portuguese, aiming to develop a reliable and relevant virtual
assistant for healthcare professionals. The HealthCareMagic-100k-en and MedQuAD
datasets, translated from English using GPT-3.5, were used to fine-tune the
ChatBode-7B model using the PEFT-QLoRA method. The InternLM2 model, with
initial training on medical data, presented the best overall performance, with
high precision and adequacy in metrics such as accuracy, completeness and
safety. However, DrBode models, derived from ChatBode, exhibited a phenomenon
of catastrophic forgetting of acquired medical knowledge. Despite this, these
models performed frequently or even better in aspects such as grammaticality
and coherence. A significant challenge was low inter-rater agreement,
highlighting the need for more robust assessment protocols. This work paves the
way for future research, such as evaluating multilingual models specific to the
medical field, improving the quality of training data, and developing more
consistent evaluation methodologies for the medical field.
