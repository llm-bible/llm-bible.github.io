---
layout: publication
title: 'Revisiting LRP: Positional Attribution As The Missing Ingredient For Transformer Explainability'
authors: Yarden Bakish, Itamar Zimerman, Hila Chefer, Lior Wolf
conference: "Arxiv"
year: 2025
bibkey: bakish2025revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02138"}
tags: ['Transformer', 'Tools', 'Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Interpretability', 'Pretraining Methods']
---
The development of effective explainability tools for Transformers is a crucial pursuit in deep learning research. One of the most promising approaches in this domain is Layer-wise Relevance Propagation (LRP), which propagates relevance scores backward through the network to the input space by redistributing activation values based on predefined rules. However, existing LRP-based methods for Transformer explainability entirely overlook a critical component of the Transformer architecture: its positional encoding (PE), resulting in violation of the conservation property, and the loss of an important and unique type of relevance, which is also associated with structural and positional features. To address this limitation, we reformulate the input space for Transformer explainability as a set of position-token pairs. This allows us to propose specialized theoretically-grounded LRP rules designed to propagate attributions across various positional encoding methods, including Rotary, Learnable, and Absolute PE. Extensive experiments with both fine-tuned classifiers and zero-shot foundation models, such as LLaMA 3, demonstrate that our method significantly outperforms the state-of-the-art in both vision and NLP explainability tasks. Our code is publicly available.
