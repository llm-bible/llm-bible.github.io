---
layout: publication
title: "Language-conditioned Offline RL For Multi-robot Navigation"
authors: Morad Steven, Shankar Ajay, Blumenkamp Jan, Prorok Amanda
conference: "Arxiv"
year: 2024
bibkey: morad2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20164"}
tags: ['Agentic', 'Reinforcement Learning']
---
We present a method for developing navigation policies for multi-robot teams that interpret and follow natural language instructions. We condition these policies on embeddings from pretrained Large Language Models (LLMs) and train them via offline reinforcement learning with as little as 20 minutes of randomly-collected data. Experiments on a team of five real robots show that these policies generalize well to unseen commands indicating an understanding of the LLM latent space. Our method requires no simulators or environment models and produces low-latency control policies that can be deployed directly to real robots without finetuning. We provide videos of our experiments at https://sites.google.com/view/llm-marl."
