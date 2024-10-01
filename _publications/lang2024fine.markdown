---
layout: publication
title: 'Fine-tuning Language Models With Reward Learning On Policy'
authors: Lang Hao, Huang Fei, Li Yongbin
conference: "Arxiv"
year: 2024
bibkey: lang2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19279"}
  - {name: "Code", url: "https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/rlp"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
'Reinforcement learning from human feedback (RLHF) has emerged as an effective approach to aligning large language models (LLMs) to human preferences. RLHF contains three steps, i.e., human preference collecting, reward learning, and policy optimization, which are usually performed serially. Despite its popularity, however, (fixed) reward models may suffer from inaccurate off-distribution, since policy optimization continuously shifts LLMs'' data distribution. Repeatedly collecting new preference data from the latest LLMs may alleviate this issue, which unfortunately makes the resulting system more complicated and difficult to optimize. In this paper, we propose reward learning on policy (RLP), an unsupervised framework that refines a reward model using policy samples to keep it on-distribution. Specifically, an unsupervised multi-view learning method is introduced to learn robust representations of policy samples. Meanwhile, a synthetic preference generation approach is developed to simulate high-quality preference data with policy outputs. Extensive experiments on three benchmark datasets show that RLP consistently outperforms the state-of-the-art. Our code is available at \url\{https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/rlp\}.'
