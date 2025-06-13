---
layout: publication
title: 'Update Your Transformer To The Latest Release: Re-basin Of Task Vectors'
authors: Filippo Rinaldi, Giacomo Capitani, Lorenzo Bonicelli, Donato Crisostomi, Federico Bolelli, Elisa Ficarra, Emanuele Rodolà, Simone Calderara, Angelo Porrello
conference: "Arxiv"
year: 2025
bibkey: rinaldi2025update
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22697"}
  - {name: "Code", url: "https://github.com/aimagelab/TransFusion"}
tags: ['Fine-Tuning', 'Transformer', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Foundation models serve as the backbone for numerous specialized models developed through fine-tuning. However, when the underlying pretrained model is updated or retrained (e.g., on larger and more curated datasets), the fine-tuned model becomes obsolete, losing its utility and requiring retraining. This raises the question: is it possible to transfer fine-tuning to a new release of the model? In this work, we investigate how to transfer fine-tuning to a new checkpoint without having to re-train, in a data-free manner. To do so, we draw principles from model re-basin and provide a recipe based on weight permutations to re-base the modifications made to the original base model, often called task vector. In particular, our approach tailors model re-basin for Transformer models, taking into account the challenges of residual connections and multi-head attention layers. Specifically, we propose a two-level method rooted in spectral theory, initially permuting the attention heads and subsequently adjusting parameters within select pairs of heads. Through extensive experiments on visual and textual tasks, we achieve the seamless transfer of fine-tuned knowledge to new pre-trained backbones without relying on a single training step or datapoint. Code is available at https://github.com/aimagelab/TransFusion.
