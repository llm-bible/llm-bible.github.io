---
layout: publication
title: 'HSI: Head-specific Intervention Can Induce Misaligned AI Coordination In Large Language Models'
authors: Paul Darm, Annalisa Riccardi
conference: "Arxiv"
year: 2025
bibkey: darm2025head
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05945"}
  - {name: "Code", url: "https://github.com/PaulDrm/targeted_intervention"}
tags: ['Fine-Tuning', 'Responsible AI', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Robust alignment guardrails for large language models are becoming
increasingly important with their widespread application. In contrast to
previous studies, we demonstrate that inference-time activation interventions
can bypass safety alignments and effectively steer model generations towards
harmful AI coordination for Llama 2. Our method applies fine-grained
interventions at specific model subcomponents, particularly attention heads,
using a simple binary choice probing strategy. These interventions then
generalise to the open-ended generation setting effectively circumventing
safety guardrails. We show that probing single attention heads is more
effective than intervening on full layers and intervening on only four
attention heads is comparable to supervised fine-tuning. We further show that
only a few example completions are needed to compute effective steering
directions, which is an advantage over classical fine-tuning. Our findings
highlight the shortcomings of current alignment techniques. In addition, our
results suggest that, at the attention head level, activations encode
fine-grained linearly separable behaviors. Practically, the approach offers a
straightforward methodology to steer large language model behaviour, which
could be extended to diverse domains beyond safety requiring fine-grained
control over the model output. The code and datasets for this study can be
found on https://github.com/PaulDrm/targeted_intervention.
