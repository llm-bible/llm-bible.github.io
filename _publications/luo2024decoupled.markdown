---
layout: publication
title: 'Decoupled Alignment For Robust Plug-and-play Adaptation'
authors: Haozheng Luo, Jiahao Yu, Wenxin Zhang, Jialong Li, Jerry Yao-chieh Hu, Xinyu Xing, Han Liu
conference: "Arxiv"
year: 2024
bibkey: luo2024decoupled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01514"}
tags: ['Responsible AI', 'Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Distillation', 'Pretraining Methods', 'Fine-Tuning']
---
We introduce a low-resource safety enhancement method for aligning large
language models (LLMs) without the need for supervised fine-tuning (SFT) or
reinforcement learning from human feedback (RLHF). Our main idea is to exploit
knowledge distillation to extract the alignment information from existing
well-aligned LLMs and integrate it into unaligned LLMs in a plug-and-play
fashion. Methodology, we employ delta debugging to identify the critical
components of knowledge necessary for effective distillation. On the harmful
question dataset, our method significantly enhances the average defense success
rate by approximately 14.41%, reaching as high as 51.39%, in 17 unaligned
pre-trained LLMs, without compromising performance.
