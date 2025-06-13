---
layout: publication
title: 'Machine-generated Text Detection Prevents Language Model Collapse'
authors: George Drayson, Emine Yilmaz, Vasileios Lampos
conference: "Arxiv"
year: 2025
bibkey: drayson2025machine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15654"}
tags: ['Training Techniques', 'Model Architecture', 'Language Modeling', 'GPT', 'Pre-Training', 'Applications']
---
As Large Language Models (LLMs) become increasingly prevalent, their generated outputs are proliferating across the web, risking a future where machine-generated content dilutes human-authored text. Since online data is the primary resource for LLM pre-training, subsequent models could be trained on an unknown portion of synthetic samples. This will lead to model collapse, a degenerative process whereby LLMs reinforce their own errors, converge to a low variance output distribution, and ultimately yield a declining performance. In this study, we investigate the impact of decoding strategy on model collapse, analysing the text characteristics at each model generation, the similarity to human references, and the resulting model performance. Using the decoding strategies that lead to the most significant degradation, we evaluate model collapse in more realistic scenarios where the origin of the data (human or synthetic) is unknown. We train a machine-generated text detector and propose an importance sampling approach to alleviate model collapse. Our method is validated on two LLM variants (GPT-2 and SmolLM2), across a range of model sizes (124M to 1.7B), on the open-ended text generation task. We demonstrate that it can not only prevent model collapse but also improve performance when sufficient human-authored samples are present. Source code: github.com/GeorgeDrayson/model_collapse.
