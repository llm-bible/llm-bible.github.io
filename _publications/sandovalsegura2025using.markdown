---
layout: publication
title: 'Using Attention Sinks To Identify And Evaluate Dormant Heads In Pretrained Llms'
authors: Pedro Sandoval-segura, Xijun Wang, Ashwinee Panda, Micah Goldblum, Ronen Basri, Tom Goldstein, David Jacobs
conference: "Arxiv"
year: 2025
bibkey: sandovalsegura2025using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03889"}
tags: ['RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Multi-head attention is foundational to large language models (LLMs),
enabling different heads to have diverse focus on relevant input tokens.
However, learned behaviors like attention sinks, where the first token receives
most attention despite limited semantic importance, challenge our understanding
of multi-head attention. To analyze this phenomenon, we propose a new
definition for attention heads dominated by attention sinks, known as dormant
attention heads. We compare our definition to prior work in a model
intervention study where we test whether dormant heads matter for inference by
zeroing out the output of dormant attention heads. Using six pretrained models
and five benchmark datasets, we find our definition to be more model and
dataset-agnostic. Using our definition on most models, more than 4% of a
model's attention heads can be zeroed while maintaining average accuracy, and
zeroing more than 14% of a model's attention heads can keep accuracy to within
1% of the pretrained model's average accuracy. Further analysis reveals that
dormant heads emerge early in pretraining and can transition between dormant
and active states during pretraining. Additionally, we provide evidence that
they depend on characteristics of the input text.
