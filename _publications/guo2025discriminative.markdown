---
layout: publication
title: 'Discriminative Finetuning Of Generative Large Language Models Without Reward Models And Human Preference Data'
authors: Siqi Guo, Ilgee Hong, Vicente Balmaseda, Changlong Yu, Liang Qiu, Xin Liu, Haoming Jiang, Tuo Zhao, Tianbao Yang
conference: "Arxiv"
year: 2025
bibkey: guo2025discriminative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18679"}
  - {name: "Code", url: "https://github.com/Optimization-AI/DFT"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Supervised fine-tuning (SFT) has become a crucial step for aligning pretrained large language models (LLMs) using supervised datasets of input-output pairs. However, despite being supervised, SFT is inherently limited by its generative training objective. To address its limitations, the existing common strategy is to follow SFT with a separate phase of preference optimization (PO), which relies on either human-labeled preference data or a strong reward model to guide the learning process. In this paper, we address the limitations of SFT by exploring one of the most successful techniques in conventional supervised learning: discriminative learning. We introduce Discriminative Fine-Tuning (DFT), an improved variant of SFT, which mitigates the burden of collecting human-labeled preference data or training strong reward models. Unlike SFT that employs a generative approach and overlooks negative data, DFT adopts a discriminative paradigm that increases the probability of positive answers while suppressing potentially negative ones, aiming for data prediction instead of token prediction. Our contributions include: (i) a discriminative probabilistic framework for fine-tuning LLMs by explicitly modeling the discriminative likelihood of an answer among all possible outputs given an input; (ii) efficient algorithms to optimize this discriminative likelihood; and (iii) extensive experiments demonstrating DFT's effectiveness, achieving performance better than SFT and comparable to if not better than SFT\\(\rightarrow\\)PO. The code can be found at https://github.com/Optimization-AI/DFT.
