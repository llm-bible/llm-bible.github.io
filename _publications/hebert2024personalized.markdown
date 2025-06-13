---
layout: publication
title: 'PERSOMA: Personalized Soft Prompt Adapter Architecture For Personalized Language Prompting'
authors: Liam Hebert, Krishna Sayana, Ambarish Jash, Alexandros Karatzoglou, Sukhdeep Sodhi, Sumanth Doddapaneni, Yanli Cai, Dima Kuzmin
conference: "Arxiv"
year: 2024
bibkey: hebert2024personalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.00960"}
tags: ['Prompting', 'Model Architecture', 'Fine-Tuning']
---
Understanding the nuances of a user's extensive interaction history is key to
building accurate and personalized natural language systems that can adapt to
evolving user preferences. To address this, we introduce PERSOMA, Personalized
Soft Prompt Adapter architecture. Unlike previous personalized prompting
methods for large language models, PERSOMA offers a novel approach to
efficiently capture user history. It achieves this by resampling and
compressing interactions as free form text into expressive soft prompt
embeddings, building upon recent research utilizing embedding representations
as input for LLMs. We rigorously validate our approach by evaluating various
adapter architectures, first-stage sampling strategies, parameter-efficient
tuning techniques like LoRA, and other personalization methods. Our results
demonstrate PERSOMA's superior ability to handle large and complex user
histories compared to existing embedding-based and text-prompt-based
techniques.
