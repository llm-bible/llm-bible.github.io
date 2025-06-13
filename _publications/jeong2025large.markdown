---
layout: publication
title: 'Large Language Models Are Better Logical Fallacy Reasoners With Counterargument, Explanation, And Goal-aware Prompt Formulation'
authors: Jiwon Jeong, Hyeju Jang, Hogun Park
conference: "Arxiv"
year: 2025
bibkey: jeong2025large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23363'}
tags: ['GPT', 'Interpretability and Explainability', 'Prompting', 'Model Architecture']
---
The advancement of Large Language Models (LLMs) has greatly improved our
ability to process complex language. However, accurately detecting logical
fallacies remains a significant challenge. This study presents a novel and
effective prompt formulation approach for logical fallacy detection, applicable
in both supervised (fine-tuned) and unsupervised (zero-shot) settings. Our
method enriches input text incorporating implicit contextual information --
counterarguments, explanations, and goals -- which we query for validity within
the context of the argument. We then rank these queries based on confidence
scores to inform classification. We evaluate our approach across multiple
datasets from 5 domains, covering 29 distinct fallacy types, using models from
the GPT and LLaMA series. The results show substantial improvements over
state-of-the-art models, with F1 score increases of up to 0.60 in zero-shot
settings and up to 0.45 in fine-tuned models. Extensive analyses further
illustrate why and how our method excels.
