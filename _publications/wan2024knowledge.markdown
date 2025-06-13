---
layout: publication
title: 'Fusechat: Knowledge Fusion Of Chat Models'
authors: Fanqi Wan, Longguang Zhong, Ziyi Yang, Ruijun Chen, Xiaojun Quan
conference: "Arxiv"
year: 2024
bibkey: wan2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.07990"}
  - {name: "Code", url: "https://github.com/fanqiwan/FuseAI"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Merging', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
While training large language models (LLMs) from scratch can indeed lead to
models with distinct capabilities and strengths, it incurs substantial costs
and may lead to redundancy in competencies. Knowledge fusion aims to integrate
existing LLMs of diverse architectures and capabilities into a more potent LLM
through lightweight continual training, thereby reducing the need for costly
LLM development. In this work, we propose a new framework for the knowledge
fusion of chat LLMs through two main stages, resulting in FuseChat. Firstly, we
conduct pairwise knowledge fusion on source chat LLMs of varying structures and
scales to create multiple target LLMs with identical structure and size via
lightweight fine-tuning. During this process, a statistics-based token
alignment approach is introduced as the cornerstone for fusing LLMs with
different structures. Secondly, we merge these target LLMs within the parameter
space, where we propose a novel method for determining the merging coefficients
based on the magnitude of parameter updates before and after fine-tuning. We
implement and validate FuseChat using six prominent chat LLMs with diverse
architectures and scales, including OpenChat-3.5-7B, Starling-LM-7B-alpha,
NH2-SOLAR-10.7B, InternLM2-Chat-20B, Mixtral-8x7B-Instruct, and
Qwen-1.5-Chat-72B. Experimental results on two instruction-following
benchmarks, AlpacaEval 2.0 and MT-Bench, demonstrate the superiority of
FuseChat-7B over baselines of various sizes. Our model is even comparable to
the larger Mixtral-8x7B-Instruct and approaches GPT-3.5-Turbo-1106 on MT-Bench.
Our code, model weights, and data are public at
\url\{https://github.com/fanqiwan/FuseAI\}.
