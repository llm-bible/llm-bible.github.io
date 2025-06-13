---
layout: publication
title: 'Pipeline Analysis For Developing Instruct Llms In Low-resource Languages: A Case Study On Basque'
authors: Ander Corral, Ixak Sarasua, Xabier Saralegi
conference: "Arxiv"
year: 2024
bibkey: corral2024pipeline
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.13922"}
tags: ['Pre-Training', 'Training Techniques', 'Applications']
---
Large language models (LLMs) are typically optimized for resource-rich
languages like English, exacerbating the gap between high-resource and
underrepresented languages. This work presents a detailed analysis of
strategies for developing a model capable of following instructions in a
low-resource language, specifically Basque, by focusing on three key stages:
pre-training, instruction tuning, and alignment with human preferences. Our
findings demonstrate that continual pre-training with a high-quality Basque
corpus of around 600 million words improves natural language understanding
(NLU) of the foundational model by over 12 points. Moreover, instruction tuning
and human preference alignment using automatically translated datasets proved
highly effective, resulting in a 24-point improvement in instruction-following
performance. The resulting models, Llama-eus-8B and Llama-eus-8B-instruct,
establish a new state-of-the-art for Basque in the sub-10B parameter category.
