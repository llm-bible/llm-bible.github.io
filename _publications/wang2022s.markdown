---
layout: publication
title: 'S-prompts Learning With Pre-trained Transformers: An Occam''s Razor For Domain Incremental Learning'
authors: Wang Yabin, Huang Zhiwu, Hong Xiaopeng
conference: "Arxiv"
year: 2022
bibkey: wang2022s
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.12819"}
  - {name: "Code", url: "https://github.com/iamwangyabin/S-Prompts"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
State-of-the-art deep neural networks are still struggling to address the catastrophic forgetting problem in continual learning. In this paper, we propose one simple paradigm (named as S-Prompting) and two concrete approaches to highly reduce the forgetting degree in one of the most typical continual learning scenarios, i.e., domain increment learning (DIL). The key idea of the paradigm is to learn prompts independently across domains with pre-trained transformers, avoiding the use of exemplars that commonly appear in conventional methods. This results in a win-win game where the prompting can achieve the best for each domain. The independent prompting across domains only requests one single cross-entropy loss for training and one simple K-NN operation as a domain identifier for inference. The learning paradigm derives an image prompt learning approach and a novel language-image prompt learning approach. Owning an excellent scalability (0.03&#37; parameter increase per domain), the best of our approaches achieves a remarkable relative improvement (an average of about 30&#37;) over the best of the state-of-the-art exemplar-free methods for three standard DIL tasks, and even surpasses the best of them relatively by about 6&#37; in average when they use exemplars. Source code is available at \url\{https://github.com/iamwangyabin/S-Prompts\}.
