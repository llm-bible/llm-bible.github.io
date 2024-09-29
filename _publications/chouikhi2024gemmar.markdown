---
layout: publication
title: GemmAr Enhancing LLMs Through Arabic Instruction-Tuning
authors: Chouikhi Hasna, Aloui Manel, Hammou Cyrine Ben, Chaabane Ghaith, Kchaou Haithem, Dhaouadi Chehir
conference: "Arxiv"
year: 2024
bibkey: chouikhi2024gemmar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02147"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have greatly impacted the natural language processing (NLP) field particularly for the English language. These models have demonstrated capabilities in understanding and generating human-like text. The success of language models largely depends on the availability of high-quality instruction datasets which consist of detailed task descriptions and corresponding responses that are essential for training the models to address a variety of prompts accurately. However the availability and quality of these resources vary by language. While models perform well in English they often need help with languages like Arabic due to the lack of datasets for fine-tuning Arabic-specific tasks. To address this issue we introduce InstAr-500k a new Arabic instruction dataset created by generating and collecting content that covers several domains and instruction types. We assess this dataset by fine-tuning an open-source Gemma-7B model on several downstream tasks to improve its functionality. Based on multiple evaluations our fine-tuned model achieves excellent performance on several Arabic NLP benchmarks. These outcomes emphasize the effectiveness of our dataset in elevating the capabilities of language models for Arabic. Our instruction dataset bridges the performance gap between English and Arabic language models by providing resources that amplify Arabic NLP development. Building on this foundation we developed a model GemmAr-7B-V1 specifically tuned to excel at a wide range of Arabic NLP tasks.
