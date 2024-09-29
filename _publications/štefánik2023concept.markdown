---
layout: publication
title: Concept-aware Training Improves In-context Learning Ability Of Language Models
authors: Štefánik Michal, Kadlčík Marek
conference: "Arxiv"
year: 2023
bibkey: štefánik2023concept
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13775"}
tags: ['In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Many recent language models (LMs) of Transformers family exhibit so-called in-context learning (ICL) ability manifested in the LMs ability to modulate their function by a task described in a natural language input. Previous work curating these models assumes that ICL emerges from vast over-parametrization or the scale of multi-task training. However a complementary branch of recent theoretical work attributes ICL emergence to specific properties of training data and creates functional in-context learners in small-scale synthetic settings. Inspired by recent findings on data properties driving the emergence of ICL we propose a method to create LMs able to better utilize the in-context information by constructing training scenarios where it is beneficial for the LM to capture the analogical reasoning concepts. We measure that data sampling of Concept-aware Training (CoAT) consistently improves models reasoning ability. As a result the in-context learners trained with CoAT on only two datasets of a single (QA) task perform comparably to larger models trained on 1600+ tasks.
