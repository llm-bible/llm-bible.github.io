---
layout: publication
title: 'Pruning The Paradox: How Clip''s Most Informative Heads Enhance Performance While Amplifying Bias'
authors: Avinash Madasu, Vasudev Lal, Phillip Howard
conference: "Arxiv"
year: 2025
bibkey: madasu2025pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11103"}
tags: ['Pre-Training', 'GPT', 'Efficiency and Optimization', 'Ethics and Bias', 'Interpretability and Explainability', 'Model Architecture', 'Pruning', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models', 'Prompting', 'In-Context Learning']
---
CLIP is one of the most popular foundational models and is heavily used for many vision-language tasks. However, little is known about the inner workings of CLIP. While recent work has proposed decomposition-based interpretability methods for identifying textual descriptions of attention heads in CLIP, the implications of conceptual consistency in these text labels on interpretability and model performance has not been explored. To bridge this gap, we study the conceptual consistency of text descriptions for attention heads in CLIP-like models. We conduct extensive experiments on six different models from OpenAI and OpenCLIP which vary by size, type of pre-training data and patch size. We propose Concept Consistency Score (CCS), a novel interpretability metric that measures how consistently individual attention heads in CLIP models align with specific concepts. To assign concept labels to heads, we use in-context learning with ChatGPT, guided by a few manually-curated examples, and validate these labels using an LLM-as-a-judge approach. Our soft-pruning experiments reveal that high CCS heads are critical for preserving model performance, as pruning them leads to a significantly larger performance drop than pruning random or low CCS heads. Notably, we find that high CCS heads capture essential concepts and play a key role in out-of-domain detection, concept-specific reasoning, and video-language understanding. Moreover, we prove that high CCS heads learn spurious correlations amplifying social biases. These results position CCS as a powerful interpretability metric exposing the paradox of performance and social biases in CLIP models.
