---
layout: publication
title: 'Aligning Large Language Models With Counterfactual DPO'
authors: Bradley Butcher
conference: "Arxiv"
year: 2024
bibkey: butcher2024aligning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.09566'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Advancements in large language models (LLMs) have demonstrated remarkable
capabilities across a diverse range of applications. These models excel in
generating text completions that are contextually coherent and cover an
extensive array of subjects. However, the vast datasets required for their
training make aligning response styles during the pretraining and instruction
tuning phases challenging. Consequently, an additional alignment phase is
typically employed, wherein the model is further trained with human preference
data to better align its outputs with human expectations. While this process
doesn't introduce new capabilities per se, it does accentuate generation styles
innate to the model. This paper explores the utilization of counterfactual
prompting within the framework of Direct Preference Optimization (DPO) to align
the model's style without relying on human intervention. We demonstrate that
this method effectively instils desirable behaviour, mitigates undesirable
ones, and encourages the model to disregard inappropriate instructions. Our
findings suggest that counterfactual prompting with DPO presents a low-resource
way to fine-tune LLMs to meet the demands for responsible and ethically aligned
AI systems.
