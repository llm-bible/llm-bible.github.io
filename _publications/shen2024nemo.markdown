---
layout: publication
title: Nemo-aligner: Scalable Toolkit For Efficient Model Alignment
authors: Shen Gerald, Wang Zhilin, Delalleau Olivier, Zeng Jiaqi, Dong Yi, Egert Daniel, Sun Shengyang, Zhang Jimmy, Jain Sahil, Taghibakhshi Ali, Ausin Markel Sanz, Aithal Ashwath, Kuchaiev Oleksii
conference: "Arxiv"
year: 2024
bibkey: shen2024nemo
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01481"}
  - {name: "Code", url: "https://github.com/NVIDIA/NeMo-Aligner"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Aligning Large Language Models (LLMs) with human values and preferences is essential for making them helpful and safe. However building efficient tools to perform alignment can be challenging especially for the largest and most competent LLMs which often contain tens or hundreds of billions of parameters. We create NeMo-Aligner a toolkit for model alignment that can efficiently scale to a thousand GPUs for training the largest open-source LLMs such as Nemotron 4 340B and Llama 3.1 405B. NeMo-Aligner comes with highly optimized and scalable implementations for major paradigms of model alignment such as Reinforcement Learning from Human Feedback (RLHF) Direct Preference Optimization (DPO) SteerLM and Self-Play Fine-Tuning (SPIN). Additionally our toolkit supports running most of the alignment techniques in a Parameter Efficient Fine-Tuning (PEFT) setting. NeMo-Aligner is designed for extensibility allowing support for other alignment techniques with minimal effort. It is open-sourced with Apache 2.0 License and we invite community contributions at https://github.com/NVIDIA/NeMo-Aligner"
