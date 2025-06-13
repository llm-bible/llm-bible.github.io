---
layout: publication
title: 'Muon Is Scalable For LLM Training'
authors: Jingyuan Liu, Jianlin Su, Xingcheng Yao, Zhejun Jiang, Guokun Lai, Yulun Du, Yidao Qin, Weixin Xu, Enzhe Lu, Junjie Yan, Yanru Chen, Huabin Zheng, Yibo Liu, Shaowei Liu, Bohong Yin, Weiran He, Han Zhu, Yuzhi Wang, Jianzhou Wang, Mengnan Dong, Zheng Zhang, Yongsheng Kang, Hao Zhang, Xinran Xu, Yutao Zhang, Yuxin Wu, Xinyu Zhou, Zhilin Yang
conference: "Arxiv"
year: 2025
bibkey: liu2025muon
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.16982'}
tags: ['Reinforcement Learning', 'Large-Scale Training', 'Efficiency and Optimization', 'Training Techniques']
---
Recently, the Muon optimizer based on matrix orthogonalization has
demonstrated strong results in training small-scale language models, but the
scalability to larger models has not been proven. We identify two crucial
techniques for scaling up Muon: (1) adding weight decay and (2) carefully
adjusting the per-parameter update scale. These techniques allow Muon to work
out-of-the-box on large-scale training without the need of hyper-parameter
tuning. Scaling law experiments indicate that Muon achieves \\(\sim\!2\times\\)
computational efficiency compared to AdamW with compute optimal training.
  Based on these improvements, we introduce Moonlight, a 3B/16B-parameter
Mixture-of-Expert (MoE) model trained with 5.7T tokens using Muon. Our model
improves the current Pareto frontier, achieving better performance with much
fewer training FLOPs compared to prior models.
  We open-source our distributed Muon implementation that is memory optimal and
communication efficient. We also release the pretrained, instruction-tuned, and
intermediate checkpoints to support future research.
