---
layout: publication
title: Text-to-Model Text-Conditioned Neural Network Diffusion for Train-Once-for-All Personalization
authors: Li Zexi, Gao Lingzhi, Wu Chao
conference: "Arxiv"
year: 2024
bibkey: li2024text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14132"}
tags: ['Few Shot', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Generative artificial intelligence (GenAI) has made significant progress in understanding world knowledge and generating content from human languages across various modalities like text-to-text large language models text-to-image stable diffusion and text-to-video Sora. While in this paper we investigate the capability of GenAI for text-to-model generation to see whether GenAI can comprehend hyper-level knowledge embedded within AI itself parameters. Specifically we study a practical scenario termed train-once-for-all personalization aiming to generate personalized models for diverse end-users and tasks using text prompts. Inspired by the recent emergence of neural network diffusion we present Tina a text-conditioned neural network diffusion for train-once-for-all personalization. Tina leverages a diffusion transformer model conditioned on task descriptions embedded using a CLIP model. Despite the astronomical number of potential personalized tasks (e.g. 1.73×10^13) by our design Tina demonstrates remarkable in-distribution and out-of-distribution generalization even trained on small datasets ( 1000). We further verify whether and how understands world knowledge by analyzing its capabilities under zero-shot/few-shot image prompts different numbers of personalized classes prompts of natural language descriptions and predicting unseen entities.
