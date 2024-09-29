---
layout: publication
title: FP845;LM Training FP8 Large Language Models
authors: Peng Houwen, Wu Kan, Wei Yixuan, Zhao Guoshuai, Yang Yuxiang, Liu Ze, Xiong Yifan, Yang Ziyue, Ni Bolin, Hu Jingcheng, Li Ruihang, Zhang Miaosen, Li Chen, Ning Jia, Wang Ruizhe, Zhang Zheng, Liu Shuguang, Chau Joe, Hu Han, Cheng Peng
conference: "Arxiv"
year: 2023
bibkey: peng2023training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18313"}
  - {name: "Code", url: "https://github.com/Azure/MS&#45;AMP&#125;&#123;aka.ms/MS.AMP&#125;"}
tags: ['Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
In this paper we explore FP8 low45;bit data formats for efficient training of large language models (LLMs). Our key insight is that most variables such as gradients and optimizer states in LLM training can employ low45;precision data formats without compromising model accuracy and requiring no changes to hyper45;parameters. Specifically we propose a new FP8 automatic mixed45;precision framework for training LLMs. This framework offers three levels of FP8 utilization to streamline mixed45;precision and distributed parallel training for LLMs. It gradually incorporates 845;bit gradients optimizer states and distributed learning in an incremental manner. Experiment results show that during the training of GPT45;175B model on H100 GPU platform our FP8 mixed45;precision training framework not only achieved a remarkable 3937; reduction in real memory usage but also ran 7537; faster than the widely adopted BF16 framework (i.e. Megatron45;LM) surpassing the speed of Nvidia Transformer Engine by 3737;. This largely reduces the training costs for large foundation models. Furthermore our FP8 mixed45;precision training methodology is generic. It can be seamlessly applied to other tasks such as LLM instruction tuning and reinforcement learning with human feedback offering savings in fine45;tuning expenses. Our FP8 low45;precision training framework is open45;sourced at 123;https://github.com/Azure/MS&#45;AMP&#125;&#123;aka.ms/MS.AMP&#125;.
