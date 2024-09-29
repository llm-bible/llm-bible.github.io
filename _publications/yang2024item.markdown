---
layout: publication
title: "Item-language Model For Conversational Recommendation"
authors: Yang Li, Subbiah Anushya, Patel Hardik, Li Judith Yue, Song Yanwei, Mirghaderi Reza, Aggarwal Vikram
conference: "Arxiv"
year: 2024
bibkey: yang2024item
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02844"}
tags: ['Multimodal Models', 'Reinforcement Learning', 'Training Techniques']
---
Large-language Models (LLMs) have been extremely successful at tasks like complex dialogue understanding reasoning and coding due to their emergent abilities. These emergent abilities have been extended with multi-modality to include image audio and video capabilities. Recommender systems on the other hand have been critical for information seeking and item discovery needs. Recently there have been attempts to apply LLMs for recommendations. One difficulty of current attempts is that the underlying LLM is usually not trained on the recommender system data which largely contains user interaction signals and is often not publicly available. Another difficulty is user interaction signals often have a different pattern from natural language text and it is currently unclear if the LLM training setup can learn more non-trivial knowledge from interaction signals compared with traditional recommender system methods. Finally it is difficult to train multiple LLMs for different use-cases and to retain the original language and reasoning abilities when learning from recommender system data. To address these three limitations we propose an Item-Language Model (ILM) which is composed of an item encoder to produce text-aligned item representations that encode user interaction signals and a frozen LLM that can understand those item representations with preserved pretrained knowledge. We conduct extensive experiments which demonstrate both the importance of the language-alignment and of user interaction knowledge in the item encoder.
