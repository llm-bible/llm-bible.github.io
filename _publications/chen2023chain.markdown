---
layout: publication
title: 'Chain-of-thought Prompt Distillation For Multimodal Named Entity Recognition And Multimodal Relation Extraction'
authors: Chen Feng, Feng Yujian
conference: "Arxiv"
year: 2023
bibkey: chen2023chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.14122"}
tags: ['Distillation', 'Efficiency And Optimization', 'Interpretability And Explainability', 'Multimodal Models', 'Prompting']
---
Multimodal Named Entity Recognition (MNER) and Multimodal Relation Extraction (MRE) necessitate the fundamental reasoning capacity for intricate linguistic and multimodal comprehension. In this study we explore distilling the reasoning ability of large language models (LLMs) into a more compact student model by generating a (textitchain of thought) (CoT) -- a sequence of intermediate reasoning steps. Specifically we commence by exemplifying the elicitation of such reasoning ability from LLMs through CoT prompts covering multi-grain (noun sentence multimodality) and data-augmentation (style entity image) dimensions. Subsequently we present a novel conditional prompt distillation method to assimilate the commonsense reasoning ability from LLMs thereby enhancing the utility of the student model in addressing text-only inputs without the requisite addition of image and CoT knowledge. Extensive experiments reveal that our approach attains state-of-the-art accuracy and manifests a plethora of advantages concerning interpretability data efficiency and cross-domain generalization on MNER and MRE datasets.
