---
layout: publication
title: Instruction Diversity Drives Generalization To Unseen Tasks
authors: Zhang Dylan, Wang Justin, Charton Francois
conference: "Arxiv"
year: 2024
bibkey: zhang2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10891"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Instruction tuning -- fine-tuning a large language model (LLM) on pairs of instructions and desired outcomes -- is an approach that enables pre-trained language models to perform real-world tasks and follow human instructions. Its practical success depends on the model learning a broader set of instructions than those it was trained on. Yet the factors that determine model generalization to such are not well understood. To understand the driving factors of generalization In this paper we experiment with string rewrites a symbolic task that serves as a building block for Turing complete Markov algorithms while allowing experimental control of inputs and instructions. We investigate the trade-off between the number of instructions the model is trained on and the number of training samples provided for each instruction and observe that the diversity of the instruction set determines generalization. Generalization emerges once a diverse enough set of tasks is provided even though very few examples are provided for each task. Instruction diversity also ensures robustness with respect to non-uniform distributions of instructions in the training set.
