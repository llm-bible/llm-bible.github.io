---
layout: publication
title: 'Mabvit -- Modified Attention Block Enhances Vision Transformers'
authors: Ramesh Mahesh, Ramkumar Aswinkumar
conference: "Arxiv"
year: 2023
bibkey: ramesh2023mabvit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01324"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
'Recent studies have demonstrated the effectiveness of Gated Linear Units (GLU) in enhancing transformer models, particularly in Large Language Models (LLMs). Additionally, utilizing a parallel configuration within each Transformer block rather than the conventional serialized method has been revealed to accelerate the training of LLMs without significantly impacting performance. However, when the MLP and attention block were run in parallel for the image classification task, we observed a noticeable decline in performance. We propose a novel transformer variant that integrates non-linearity within the attention block to tackle this problem. We implemented the GLU-based activation function on the Value tensor, and this new technique surpasses the current state-of-the-art S/16 variant of Vision Transformers by 0.6&#37; on the ImageNet-1K dataset while utilizing fewer parameters. It also supersedes the B/16 variant while using only half the parameters. Furthermore, we provide results with the GELU activation function variant to confirm our assertions. Lastly, we showcase that the MABViT variants exhibit greater potential when utilized in deep transformers compared to the standard architecture.'
