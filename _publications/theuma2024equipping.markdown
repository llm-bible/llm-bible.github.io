---
layout: publication
title: 'Equipping Language Models With Tool Use Capability For Tabular Data Analysis In Finance'
authors: Adrian Theuma, Ehsan Shareghi
conference: "Arxiv"
year: 2024
bibkey: theuma2024equipping
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.15328'}
tags: ['GPT', 'Tools', 'Training Techniques', 'Fine-Tuning', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have exhibited an array of reasoning
capabilities but face challenges like error propagation and hallucination,
particularly in specialised areas like finance, where data is heterogeneous,
and precision is paramount. We explore the potential of language model
augmentation with external tools to mitigate these limitations and offload
certain reasoning steps to external tools that are more suited for the task,
instead of solely depending on the LLM's inherent abilities. More concretely,
using financial domain question-answering datasets, we apply supervised
fine-tuning on a LLaMA-2 13B Chat model to act both as a 'task router' and
'task solver'. The 'task router' dynamically directs a question to either be
answered internally by the LLM or externally via the right tool from the tool
set. Our tool-equipped SFT model, Raven, demonstrates an improvement of 35.2%
and 5.06% over the base model and SFT-only baselines, respectively, and is
highly competitive with strong GPT-3.5 results. To the best of our knowledge,
our work is the first that investigates tool augmentation of language models
for the finance domain.
