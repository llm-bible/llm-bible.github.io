---
layout: publication
title: 'Ask A Local: Detecting Hallucinations With Specialized Model Divergence'
authors: Aldan Creo, Héctor Cerezo-costas, Pedro Alonso-doval, Maximiliano Hormazábal-lagos
conference: "Arxiv"
year: 2025
bibkey: creo2025ask
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.03357'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Model Architecture']
---
Hallucinations in large language models (LLMs) - instances where models generate plausible but factually incorrect information - present a significant challenge for AI.
  We introduce "Ask a Local", a novel hallucination detection method exploiting the intuition that specialized models exhibit greater surprise when encountering domain-specific inaccuracies. Our approach computes divergence between perplexity distributions of language-specialized models to identify potentially hallucinated spans. Our method is particularly well-suited for a multilingual context, as it naturally scales to multiple languages without the need for adaptation, relying on external data sources, or performing training. Moreover, we select computationally efficient models, providing a scalable solution that can be applied to a wide range of languages and domains.
  Our results on a human-annotated question-answer dataset spanning 14 languages demonstrate consistent performance across languages, with Intersection-over-Union (IoU) scores around 0.3 and comparable Spearman correlation values. Our model shows particularly strong performance on Italian and Catalan, with IoU scores of 0.42 and 0.38, respectively, while maintaining cross-lingual effectiveness without language-specific adaptations. We release our code and architecture to facilitate further research in multilingual hallucination detection.
