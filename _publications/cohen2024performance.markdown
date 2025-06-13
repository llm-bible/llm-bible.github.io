---
layout: publication
title: 'Performance Gap In Entity Knowledge Extraction Across Modalities In Vision Language Models'
authors: Ido Cohen, Daniela Gottesman, Mor Geva, Raja Giryes
conference: "Arxiv"
year: 2024
bibkey: cohen2024performance
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.14133'}
tags: ['Interpretability and Explainability', 'RAG', 'Efficiency and Optimization', 'Tools', 'Multimodal Models']
---
Vision-language models (VLMs) excel at extracting and reasoning about
information from images. Yet, their capacity to leverage internal knowledge
about specific entities remains underexplored. This work investigates the
disparity in model performance when answering factual questions about an entity
described in text versus depicted in an image. Our results reveal a significant
accuracy drop --averaging 19%-- when the entity is presented visually instead
of textually. We hypothesize that this decline arises from limitations in how
information flows from image tokens to query tokens. We use mechanistic
interpretability tools to reveal that, although image tokens are preprocessed
by the vision encoder, meaningful information flow from these tokens occurs
only in the much deeper layers. Furthermore, critical image processing happens
in the language model's middle layers, allowing few layers for consecutive
reasoning, highlighting a potential inefficiency in how the model utilizes its
layers for reasoning. These insights shed light on the internal mechanics of
VLMs and offer pathways for enhancing their reasoning capabilities.
