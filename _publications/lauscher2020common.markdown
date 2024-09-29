---
layout: publication
title: Common Sense or World Knowledge Investigating Adapter-Based Knowledge Injection into Pretrained Transformers
authors: Lauscher Anne, Majewska Olga, Ribeiro Leonardo F. R., Gurevych Iryna, Rozanov Nikolai, Glavaš Goran
conference: "Arxiv"
year: 2020
bibkey: lauscher2020common
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.11787"}
  - {name: "Code", url: "https://github.com/wluper/retrograph"}
tags: ['BERT', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Following the major success of neural language models (LMs) such as BERT or GPT-2 on a variety of language understanding tasks recent work focused on injecting (structured) knowledge from external resources into these models. While on the one hand joint pretraining (i.e. training from scratch adding objectives based on external knowledge to the primary LM objective) may be prohibitively computationally expensive post-hoc fine-tuning on external knowledge on the other hand may lead to the catastrophic forgetting of distributional knowledge. In this work we investigate models for complementing the distributional knowledge of BERT with conceptual knowledge from ConceptNet and its corresponding Open Mind Common Sense (OMCS) corpus respectively using adapter training. While overall results on the GLUE benchmark paint an inconclusive picture a deeper analysis reveals that our adapter-based models substantially outperform BERT (up to 15-20 performance points) on inference tasks that require the type of conceptual knowledge explicitly present in ConceptNet and OMCS. All code and experiments are open sourced under https://github.com/wluper/retrograph .
