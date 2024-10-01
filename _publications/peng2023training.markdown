---
layout: publication
title: 'FP8-LM: Training FP8 Large Language Models'
authors: Peng Houwen, Wu Kan, Wei Yixuan, Zhao Guoshuai, Yang Yuxiang, Liu Ze, Xiong Yifan, Yang Ziyue, Ni Bolin, Hu Jingcheng, Li Ruihang, Zhang Miaosen, Li Chen, Ning Jia, Wang Ruizhe, Zhang Zheng, Liu Shuguang, Chau Joe, Hu Han, Cheng Peng
conference: "Arxiv"
year: 2023
bibkey: peng2023training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18313"}
  - {name: "Code", url: "https://github.com/Azure/MS-AMP}{aka.ms/MS.AMP"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
'In this paper, we explore FP8 low-bit data formats for efficient training of large language models (LLMs). Our key insight is that most variables, such as gradients and optimizer states, in LLM training can employ low-precision data formats without compromising model accuracy and requiring no changes to hyper-parameters. Specifically, we propose a new FP8 automatic mixed-precision framework for training LLMs. This framework offers three levels of FP8 utilization to streamline mixed-precision and distributed parallel training for LLMs. It gradually incorporates 8-bit gradients, optimizer states, and distributed learning in an incremental manner. Experiment results show that, during the training of GPT-175B model on H100 GPU platform, our FP8 mixed-precision training framework not only achieved a remarkable 39&#37; reduction in real memory usage but also ran 75&#37; faster than the widely adopted BF16 framework (i.e., Megatron-LM), surpassing the speed of Nvidia Transformer Engine by 37&#37;. This largely reduces the training costs for large foundation models. Furthermore, our FP8 mixed-precision training methodology is generic. It can be seamlessly applied to other tasks such as LLM instruction tuning and reinforcement learning with human feedback, offering savings in fine-tuning expenses. Our FP8 low-precision training framework is open-sourced at \{https://github.com/Azure/MS-AMP\}\{aka.ms/MS.AMP\}.'
