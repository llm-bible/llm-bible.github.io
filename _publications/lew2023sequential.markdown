---
layout: publication
title: "Sequential Monte Carlo Steering Of Large Language Models Using Probabilistic Programs"
authors: Lew Alexander K., Zhi-xuan Tan, Grand Gabriel, Mansinghka Vikash K.
conference: "Arxiv"
year: 2023
bibkey: lew2023sequential
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.03081"}
  - {name: "Code", url: "https://github.com/probcomp/hfppl),"}
tags: ['Agentic', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Even after fine-tuning and reinforcement learning large language models (LLMs) can be difficult if not impossible to control reliably with prompts alone. We propose a new inference-time approach to enforcing syntactic and semantic constraints on the outputs of LLMs called sequential Monte Carlo (SMC) steering. The key idea is to specify language generation tasks as posterior inference problems in a class of discrete probabilistic sequence models and replace standard decoding with sequential Monte Carlo inference. For a computational cost similar to that of beam search SMC can steer LLMs to solve diverse tasks including infilling generation under syntactic constraints and prompt intersection. To facilitate experimentation with SMC steering we present a probabilistic programming library LLaMPPL (https://github.com/probcomp/hfppl), for concisely specifying new generation tasks as language model probabilistic programs and automating steering of LLaMA-family Transformers.
