---
layout: publication
title: 'Can Reasoning Llms Enhance Clinical Document Classification?'
authors: Akram Mustafa, Usman Naseem, Mostafa Rahimi Azghadi
conference: "Arxiv"
year: 2025
bibkey: mustafa2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08040"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Clinical document classification is essential for converting unstructured
medical texts into standardised ICD-10 diagnoses, yet it faces challenges due
to complex medical language, privacy constraints, and limited annotated
datasets. Large Language Models (LLMs) offer promising improvements in accuracy
and efficiency for this task. This study evaluates the performance and
consistency of eight LLMs; four reasoning (Qwen QWQ, Deepseek Reasoner, GPT o3
Mini, Gemini 2.0 Flash Thinking) and four non-reasoning (Llama 3.3, GPT 4o
Mini, Gemini 2.0 Flash, Deepseek Chat); in classifying clinical discharge
summaries using the MIMIC-IV dataset. Using cTAKES to structure clinical
narratives, models were assessed across three experimental runs, with majority
voting determining final predictions. Results showed that reasoning models
outperformed non-reasoning models in accuracy (71% vs 68%) and F1 score (67% vs
60%), with Gemini 2.0 Flash Thinking achieving the highest accuracy (75%) and
F1 score (76%). However, non-reasoning models demonstrated greater stability
(91% vs 84% consistency). Performance varied across ICD-10 codes, with
reasoning models excelling in complex cases but struggling with abstract
categories. Findings indicate a trade-off between accuracy and consistency,
suggesting that a hybrid approach could optimise clinical coding. Future
research should explore multi-label classification, domain-specific
fine-tuning, and ensemble methods to enhance model reliability in real-world
applications.
