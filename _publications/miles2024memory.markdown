---
layout: publication
title: Velora Memory Efficient Training Using Rank45;1 Sub45;token Projections
authors: Miles Roy, Reddy Pradyumna, Elezi Ismail, Deng Jiankang
conference: "Arxiv"
year: 2024
bibkey: miles2024memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17991"}
tags: ['Fine Tuning', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have recently emerged as powerful tools for tackling many language45;processing tasks. Despite their success training and fine45;tuning these models is still far too computationally and memory intensive. In this paper we identify and characterise the important components needed for effective model convergence using gradient descent. In doing so we find that the intermediate activations used to implement backpropagation can be excessively compressed without incurring any degradation in performance. This result leads us to a cheap and memory45;efficient algorithm for both fine45;tuning and pre45;training LLMs. The proposed algorithm simply divides the tokens up into smaller sub45;tokens before projecting them onto a fixed 145;dimensional subspace during the forward pass. These features are then coarsely reconstructed during the backward pass to implement the update rules. We confirm the effectiveness of our algorithm as being complimentary to many state45;of45;the45;art PEFT methods on the VTAB45;1k fine45;tuning benchmark. Furthermore we outperform QLoRA for fine45;tuning LLaMA and show competitive performance against other memory45;efficient pre45;training methods on the large45;scale C4 dataset.
