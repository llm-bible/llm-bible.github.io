---
layout: publication
title: 'Ivygpt: Interactive Chinese Pathway Language Model In Medical Domain'
authors: Rongsheng Wang, Yaofei Duan, Chantong Lam, Jiexi Chen, Jiangsheng Xu, Haoming Chen, Xiaohong Liu, Patrick Cheong-iao Pang, Tao Tan
conference: "Arxiv"
year: 2023
bibkey: wang2023interactive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.10512'}
tags: ['Agentic', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
General large language models (LLMs) such as ChatGPT have shown remarkable
success. However, such LLMs have not been widely adopted for medical purposes,
due to poor accuracy and inability to provide medical advice. We propose
IvyGPT, an LLM based on LLaMA that is trained and fine-tuned with high-quality
medical question-answer (QA) instances and Reinforcement Learning from Human
Feedback (RLHF). After supervised fine-tuning, IvyGPT has good multi-turn
conversation capabilities, but it cannot perform like a doctor in other
aspects, such as comprehensive diagnosis. Through RLHF, IvyGPT can output
richer diagnosis and treatment answers that are closer to human. In the
training, we used QLoRA to train 33 billion parameters on a small number of
NVIDIA A100 (80GB) GPUs. Experimental results show that IvyGPT has outperformed
other medical GPT models.
