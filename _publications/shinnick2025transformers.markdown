---
layout: publication
title: 'Transformers Pretrained On Procedural Data Contain Modular Structures For Algorithmic Reasoning'
authors: Zachary Shinnick, Liangze Jiang, Hemanth Saratchandran, Anton Van Den Hengel, Damien Teney
conference: "Arxiv"
year: 2025
bibkey: shinnick2025transformers
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.22308'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
Pretraining on large, semantically rich datasets is key for developing language models. Surprisingly, recent studies have shown that even synthetic data, generated procedurally through simple semantic-free algorithms, can yield some of the same benefits as natural language pretraining. It is unclear what specific capabilities such simple synthetic data instils in a model, where these capabilities reside in the architecture, and how they manifest within its weights. In this short paper, we identify several beneficial forms of procedural data, together with specific algorithmic reasoning skills that improve in small transformers. Our core finding is that different procedural rules instil distinct but complementary inductive structures in the model. With extensive ablations and partial-transfer experiments, we discover that these structures reside in different parts of the model. Attention layers often carry the most transferable information, but some pretraining rules impart useful structure to MLP blocks instead. Most interestingly, the structures induced by multiple rules can be composed to jointly reinforce multiple capabilities. These results suggest an exciting possibility of disentangling the acquisition of knowledge from reasoning in language models, with the goal of improving their robustness and data efficiency.
