---
layout: publication
title: 'Amortizing Intractable Inference In Large Language Models'
authors: Edward J. Hu, Moksh Jain, Eric Elmoznino, Younesse Kaddar, Guillaume Lajoie, Yoshua Bengio, Nikolay Malkin
conference: "Arxiv"
year: 2023
bibkey: hu2023amortizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.04363"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Autoregressive large language models (LLMs) compress knowledge from their
training data through next-token conditional distributions. This limits
tractable querying of this knowledge to start-to-end autoregressive sampling.
However, many tasks of interest -- including sequence continuation, infilling,
and other forms of constrained generation -- involve sampling from intractable
posterior distributions. We address this limitation by using amortized Bayesian
inference to sample from these intractable posteriors. Such amortization is
algorithmically achieved by fine-tuning LLMs via diversity-seeking
reinforcement learning algorithms: generative flow networks (GFlowNets). We
empirically demonstrate that this distribution-matching paradigm of LLM
fine-tuning can serve as an effective alternative to maximum-likelihood
training and reward-maximizing policy optimization. As an important
application, we interpret chain-of-thought reasoning as a latent variable
modeling problem and demonstrate that our approach enables data-efficient
adaptation of LLMs to tasks that require multi-step rationalization and tool
use.
