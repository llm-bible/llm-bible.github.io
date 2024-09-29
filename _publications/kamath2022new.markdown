---
layout: publication
title: A New Path Scaling Vision45;and45;language Navigation With Synthetic Instructions And Imitation Learning
authors: Kamath Aishwarya, Anderson Peter, Wang Su, Koh Jing Yu, Ku Alexander, Waters Austin, Yang Yinfei, Baldridge Jason, Parekh Zarana
conference: "Arxiv"
year: 2022
bibkey: kamath2022new
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.03112"}
tags: ['Agentic', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Recent studies in Vision45;and45;Language Navigation (VLN) train RL agents to execute natural45;language navigation instructions in photorealistic environments as a step towards robots that can follow human instructions. However given the scarcity of human instruction data and limited diversity in the training environments these agents still struggle with complex language grounding and spatial language understanding. Pretraining on large text and image45;text datasets from the web has been extensively explored but the improvements are limited. We investigate large45;scale augmentation with synthetic instructions. We take 500+ indoor environments captured in densely45;sampled 360 degree panoramas construct navigation trajectories through these panoramas and generate a visually45;grounded instruction for each trajectory using Marky a high45;quality multilingual navigation instruction generator. We also synthesize image observations from novel viewpoints using an image45;to45;image GAN. The resulting dataset of 4.2M instruction45;trajectory pairs is two orders of magnitude larger than existing human45;annotated datasets and contains a wider variety of environments and viewpoints. To efficiently leverage data at this scale we train a simple transformer agent with imitation learning. On the challenging RxR dataset our approach outperforms all existing RL agents improving the state45;of45;the45;art NDTW from 71.1 to 79.1 in seen environments and from 64.6 to 66.8 in unseen test environments. Our work points to a new path to improving instruction45;following agents emphasizing large45;scale imitation learning and the development of synthetic instruction generation capabilities.
