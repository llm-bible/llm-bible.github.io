---
layout: publication
title: 'MURI: High-quality Instruction Tuning Datasets For Low-resource Languages Via Reverse Instructions'
authors: Abdullatif Köksal, Marion Thaler, Ayyoob Imani, Ahmet Üstün, Anna Korhonen, Hinrich Schütze
conference: "Arxiv"
year: 2024
bibkey: köksal2024high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12958"}
  - {name: "Code", url: "https://github.com/akoksal/muri"}
tags: ['Pretraining Methods', 'Training Techniques', 'Fine-Tuning', 'Has Code']
---
Instruction tuning enhances large language models (LLMs) by aligning them
with human preferences across diverse tasks. Traditional approaches to create
instruction tuning datasets face serious challenges for low-resource languages
due to their dependence on data annotation. This work introduces a novel
method, Multilingual Reverse Instructions (MURI), which generates high-quality
instruction tuning datasets for low-resource languages without requiring human
annotators or pre-existing multilingual models. Utilizing reverse instructions
and a translation pipeline, MURI produces instruction-output pairs from
existing human-written texts in low-resource languages. This method ensures
cultural relevance and diversity by sourcing texts from different native
domains and applying filters to eliminate inappropriate content. Our dataset,
MURI-IT, includes more than 2 million instruction-output pairs across 200
languages. Evaluation by native speakers and fine-tuning experiments with mT5
models demonstrate the approach's effectiveness for both NLU and open-ended
generation. We publicly release datasets and models at
https://github.com/akoksal/muri.
