---
layout: publication
title: 'Finding Skill Neurons In Pre-trained Transformer-based Language Models'
authors: Xiaozhi Wang, Kaiyue Wen, Zhengyan Zhang, Lei Hou, Zhiyuan Liu, Juanzi Li
conference: "Arxiv"
year: 2022
bibkey: wang2022finding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2211.07349'}
  - {name: "Code", url: 'https://github.com/THU-KEG/Skill-Neuron'}
tags: ['Has Code', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Pruning', 'Pre-Training', 'Pretraining Methods']
---
Transformer-based pre-trained language models have demonstrated superior
performance on various natural language processing tasks. However, it remains
unclear how the skills required to handle these tasks distribute among model
parameters. In this paper, we find that after prompt tuning for specific tasks,
the activations of some neurons within pre-trained Transformers are highly
predictive of the task labels. We dub these neurons skill neurons and confirm
they encode task-specific skills by finding that: (1) Skill neurons are crucial
for handling tasks. Performances of pre-trained Transformers on a task
significantly drop when corresponding skill neurons are perturbed. (2) Skill
neurons are task-specific. Similar tasks tend to have similar distributions of
skill neurons. Furthermore, we demonstrate the skill neurons are most likely
generated in pre-training rather than fine-tuning by showing that the skill
neurons found with prompt tuning are also crucial for other fine-tuning methods
freezing neuron weights, such as the adapter-based tuning and BitFit. We also
explore the applications of skill neurons, including accelerating Transformers
with network pruning and building better transferability indicators. These
findings may promote further research on understanding Transformers. The source
code can be obtained from https://github.com/THU-KEG/Skill-Neuron.
