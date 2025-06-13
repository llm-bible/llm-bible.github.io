---
layout: publication
title: 'AIDE: Task-specific Fine Tuning With Attribute Guided Multi-hop Data Expansion'
authors: Jiayu Li, Xuan Zhu, Fang Liu, Yanjun Qi
conference: "Arxiv"
year: 2024
bibkey: li2024task
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.06136'}
tags: ['RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) for specific tasks requires
high-quality, diverse training data relevant to the task. Recent research has
leveraged LLMs to synthesize training data, but existing approaches either
depend on large seed datasets or struggle to ensure both task relevance and
data diversity in the generated outputs. To address these challenges, we
propose AIDE, a novel data synthesis framework that uses a multi-hop process to
expand 10 seed data points while ensuring diversity and task relevance. AIDE
extracts the main topic and key knowledge attributes from the seed data to
guide the synthesis process. In each subsequent hop, it extracts the topic and
attributes from the newly generated data and continues guided synthesis. This
process repeats for a total of K hops. To prevent irrelevant data generation as
the hop depth increases, AIDE incorporates a residual connection mechanism and
uses self-reflection to improve data quality. Our empirical results demonstrate
that fine-tuning Mistral-7B, Llama-3.1-8B and Llama-3.2-3B with AIDE achieves
more than 10% accuracy improvements over the base models across 13 tasks from 5
different benchmarks, while outperforming the models fine-tuned with
state-of-the-art data synthesis methods like Evol-Instruct, DataTune and
Prompt2Model.
