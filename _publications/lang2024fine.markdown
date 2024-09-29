---
layout: publication
title: Fine45;tuning Language Models With Reward Learning On Policy
authors: Lang Hao, Huang Fei, Li Yongbin
conference: "Arxiv"
year: 2024
bibkey: lang2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.19279"}
  - {name: "Code", url: "https://github.com/AlibabaResearch/DAMO&#45;ConvAI/tree/main/rlp&#125;"}
tags: ['Agentic', 'Efficiency And Optimization', 'Has Code', 'Reinforcement Learning', 'Tools']
---
Reinforcement learning from human feedback (RLHF) has emerged as an effective approach to aligning large language models (LLMs) to human preferences. RLHF contains three steps i.e. human preference collecting reward learning and policy optimization which are usually performed serially. Despite its popularity however (fixed) reward models may suffer from inaccurate off45;distribution since policy optimization continuously shifts LLMs data distribution. Repeatedly collecting new preference data from the latest LLMs may alleviate this issue which unfortunately makes the resulting system more complicated and difficult to optimize. In this paper we propose reward learning on policy (RLP) an unsupervised framework that refines a reward model using policy samples to keep it on45;distribution. Specifically an unsupervised multi45;view learning method is introduced to learn robust representations of policy samples. Meanwhile a synthetic preference generation approach is developed to simulate high45;quality preference data with policy outputs. Extensive experiments on three benchmark datasets show that RLP consistently outperforms the state45;of45;the45;art. Our code is available at url123;https://github.com/AlibabaResearch/DAMO&#45;ConvAI/tree/main/rlp&#125;.
