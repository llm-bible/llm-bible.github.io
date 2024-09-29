---
layout: publication
title: "A New Path: Scaling Vision-and-language Navigation With Synthetic Instructions And Imitation Learning"
authors: Kamath Aishwarya, Anderson Peter, Wang Su, Koh Jing Yu, Ku Alexander, Waters Austin, Yang Yinfei, Baldridge Jason, Parekh Zarana
conference: "Arxiv"
year: 2022
bibkey: kamath2022new
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.03112"}
tags: ['Agentic', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Recent studies in Vision-and-Language Navigation (VLN) train RL agents to execute natural-language navigation instructions in photorealistic environments as a step towards robots that can follow human instructions. However given the scarcity of human instruction data and limited diversity in the training environments these agents still struggle with complex language grounding and spatial language understanding. Pretraining on large text and image-text datasets from the web has been extensively explored but the improvements are limited. We investigate large-scale augmentation with synthetic instructions. We take 500+ indoor environments captured in densely-sampled 360 degree panoramas construct navigation trajectories through these panoramas and generate a visually-grounded instruction for each trajectory using Marky a high-quality multilingual navigation instruction generator. We also synthesize image observations from novel viewpoints using an image-to-image GAN. The resulting dataset of 4.2M instruction-trajectory pairs is two orders of magnitude larger than existing human-annotated datasets and contains a wider variety of environments and viewpoints. To efficiently leverage data at this scale we train a simple transformer agent with imitation learning. On the challenging RxR dataset our approach outperforms all existing RL agents improving the state-of-the-art NDTW from 71.1 to 79.1 in seen environments and from 64.6 to 66.8 in unseen test environments. Our work points to a new path to improving instruction-following agents emphasizing large-scale imitation learning and the development of synthetic instruction generation capabilities.
