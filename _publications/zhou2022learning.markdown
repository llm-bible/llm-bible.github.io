---
layout: publication
title: 'Learning To Decompose: Hypothetical Question Decomposition Based On Comparable Texts'
authors: Ben Zhou, Kyle Richardson, Xiaodong Yu, Dan Roth
conference: "Arxiv"
year: 2022
bibkey: zhou2022learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.16865"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Pre-Training']
---
Explicit decomposition modeling, which involves breaking down complex tasks
into more straightforward and often more interpretable sub-tasks, has long been
a central theme in developing robust and interpretable NLU systems. However,
despite the many datasets and resources built as part of this effort, the
majority have small-scale annotations and limited scope, which is insufficient
to solve general decomposition tasks. In this paper, we look at large-scale
intermediate pre-training of decomposition-based transformers using distant
supervision from comparable texts, particularly large-scale parallel news. We
show that with such intermediate pre-training, developing robust
decomposition-based models for a diverse range of tasks becomes more feasible.
For example, on semantic parsing, our model, DecompT5, improves 20% to 30% on
two datasets, Overnight and TORQUE, over the baseline language model. We
further use DecompT5 to build a novel decomposition-based QA system named
DecompEntail, improving over state-of-the-art models, including GPT-3, on both
HotpotQA and StrategyQA by 8% and 4%, respectively.
