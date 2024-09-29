---
layout: publication
title: Fusechat Knowledge Fusion Of Chat Models
authors: Wan Fanqi, Zhong Longguang, Yang Ziyi, Chen Ruijun, Quan Xiaojun
conference: "Arxiv"
year: 2024
bibkey: wan2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.07990"}
  - {name: "Code", url: "https://github.com/fanqiwan/FuseAI&#125;"}
tags: ['GPT', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
While training large language models (LLMs) from scratch can indeed lead to models with distinct capabilities and strengths it incurs substantial costs and may lead to redundancy in competencies. Knowledge fusion aims to integrate existing LLMs of diverse architectures and capabilities into a more potent LLM through lightweight continual training thereby reducing the need for costly LLM development. In this work we propose a new framework for the knowledge fusion of chat LLMs through two main stages resulting in FuseChat. Firstly we conduct pairwise knowledge fusion on source chat LLMs of varying structures and scales to create multiple target LLMs with identical structure and size via lightweight fine45;tuning. During this process a statistics45;based token alignment approach is introduced as the cornerstone for fusing LLMs with different structures. Secondly we merge these target LLMs within the parameter space where we propose a novel method for determining the merging coefficients based on the magnitude of parameter updates before and after fine45;tuning. We implement and validate FuseChat using six prominent chat LLMs with diverse architectures and scales including OpenChat45;3.545;7B Starling45;LM45;7B45;alpha NH245;SOLAR45;10.7B InternLM245;Chat45;20B Mixtral45;8x7B45;Instruct and Qwen45;1.545;Chat45;72B. Experimental results on two instruction45;following benchmarks AlpacaEval 2.0 and MT45;Bench demonstrate the superiority of FuseChat45;7B over baselines of various sizes. Our model is even comparable to the larger Mixtral45;8x7B45;Instruct and approaches GPT45;3.545;Turbo45;1106 on MT45;Bench. Our code model weights and data are public at url123;https://github.com/fanqiwan/FuseAI&#125;.
