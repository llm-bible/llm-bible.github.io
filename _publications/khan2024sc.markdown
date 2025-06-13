---
layout: publication
title: 'Sc-phi2: A Fine-tuned Small Language Model For Starcraft II Macromanagement Tasks'
authors: Muhammad Junaid Khan, Gita Sukthankar
conference: "Arxiv"
year: 2024
bibkey: khan2024sc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.18989"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'GPT', 'Quantization', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Transformer', 'Prompting', 'Pre-Training']
---
This paper introduces SC-Phi2, a fine-tuned StarCraft II small language model
for macromanagement tasks. Small language models, like Phi2, Gemma, and
DistilBERT, are streamlined versions of large language models (LLMs) with fewer
parameters that require less power and memory to run. To teach Microsoft's Phi2
model about StarCraft, we create a new SC2 text dataset with information about
StarCraft races, roles, and actions and use it to fine-tune Phi-2 with
self-supervised learning. We pair this language model with a Vision Transformer
(ViT) from the pre-trained BLIP-2 (Bootstrapping Language Image Pre-training)
model, fine-tuning it on the MSC replay dataset. This enables us to construct
dynamic prompts that include visual game state information. Unlike the large
models used in StarCraft LLMs such as GPT-3.5, Phi2 is trained primarily on
textbook data and contains little inherent knowledge of StarCraft II beyond
what is provided by our training process. By using LoRA (Low-rank Adaptation)
and quantization, our model can be trained on a single GPU. We demonstrate that
our model performs well at micromanagement tasks such as build order and global
state prediction with a small number of parameters.
