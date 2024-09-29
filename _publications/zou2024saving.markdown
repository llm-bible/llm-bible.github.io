---
layout: publication
title: "Promptintern: Saving Inference Costs By Internalizing Recurrent Prompt During Large Language Model Fine-tuning"
authors: Zou Jiaru, Zhou Mengyu, Li Tao, Han Shi, Zhang Dongmei
conference: "Arxiv"
year: 2024
bibkey: zou2024saving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02211"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have played a fundamental role in various natural language processing tasks with powerful prompt techniques. However in real-world applications there are often similar prompt components for repeated queries which causes significant computational burdens during inference. Existing prompt compression and direct fine-tuning methods aim to tackle these challenges yet they frequently struggle to strike an optimal balance between cost-efficiency and performance effectiveness especially in complex tasks such as NL2Code. In this paper we propose a novel method namely PromptIntern to internalize the prompt knowledge into model parameters via progressive fine-tuning. Our method enables LLMs to emulate the human learning process for a new task where detailed templates and examples in a prompt are gradually internalized and phased out progressively as the model grows accustomed to the task. Extensive experiments demonstrate that our method reduces inference tokens over 9037; speedups inference by 4.2 times and saves 88.337; monetary cost.
