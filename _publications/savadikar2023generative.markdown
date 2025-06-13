---
layout: publication
title: 'Generative Parameter-efficient Fine-tuning'
authors: Chinmay Savadikar, Xi Song, Tianfu Wu
conference: "Arxiv"
year: 2023
bibkey: savadikar2023generative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.00700'}
tags: ['Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'GPT', 'Fine-Tuning', 'Multimodal Models', 'Ethics and Bias', 'Pretraining Methods']
---
We present Generative Parameter-Efficient Fine-Tuning (GIFT) for adapting
pretrained Transformer backbones on downstream tasks. GIFT learns to generate
the fine-tuned weights for a layer directly from its pretrained weights. The
GIFT network is parameterized in a minimally-simple way by two linear layers
(without bias terms), and is shared by different pretrained layers selected for
fine-tuning (e.g., the Query layers), which result in significantly fewer
trainable parameters compared to the layer-specific methods like Low-Rank
Adapter (LoRA). We also show this formulation bridges parameter-efficient
fine-tuning and representation fine-tuning. We perform comprehensive
experiments on natural language tasks (commonsense and arithmetic reasoning,
instruction tuning, and sequence classification) and computer vision tasks
(fine-grained classification). We obtain the best performance and parameter
efficiency among baselines on commonsense and arithmetic reasoning, and
instruction following using the Llama family of models and on visual
recognition benchmarks using Vision Transformers. Notably, compared to LoRA, we
obtain 5.7% absolute increase in average accuracy with 14 times reduction of
parameters on Commonsense170k using Llama-3 (8B), and 5.4% absolute increase in
the win rate with 4 times reduction of parameters using Llama-2 (7B) during
instruction tuning. Our GIFT also obtains a slightly higher win rate on
instruction tuning than GPT 3.5 (Turbo 1106).
