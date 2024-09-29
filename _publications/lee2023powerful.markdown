---
layout: publication
title: Platypus&#58; Quick, Cheap, And Powerful Refinement Of Llms
authors: Lee Ariel N., Hunter Cole J., Ruiz Nataniel
conference: "Arxiv"
year: 2023
bibkey: lee2023powerful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.07317"}
tags: ['Fine Tuning', 'Merging', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We present (textbfPlatypus) a family of fine-tuned and merged Large Language Models (LLMs) that achieves the strongest performance and currently stands at first place in HuggingFaces Open LLM Leaderboard as of the release date of this work. In this work we describe (1) our curated dataset (textbf)Open-Platypus that is a subset of other open datasets and which (textit)we release to the public (2) our process of fine-tuning and merging LoRA modules in order to conserve the strong prior of pretrained LLMs while bringing specific domain knowledge to the surface (3) our efforts in checking for test data leaks and contamination in the training data which can inform future research. Specifically the Platypus family achieves strong performance in quantitative LLM metrics across model sizes topping the global Open LLM leaderboard while using just a fraction of the fine-tuning data and overall compute that are required for other state-of-the-art fine-tuned LLMs. In particular a 13B Platypus model can be trained on (textit)a single A100 GPU using 25k questions in 5 hours. This is a testament of the quality of our Open-Platypus dataset and opens opportunities for more improvements in the field. Project page https://platypus-llm.github.io"
