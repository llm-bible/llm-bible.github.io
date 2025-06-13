---
layout: publication
title: 'Token-level Accept Or Reject: A Micro Alignment Approach For Large Language Models'
authors: Yang Zhang, Yu Yu, Bo Tang, Yu Zhu, Chuxiong Sun, Wenqiang Wei, Jie Hu, Zipeng Xie, Zhiyu Li, Feiyu Xiong, Edward Chung
conference: "Arxiv"
year: 2025
bibkey: zhang2025token
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19743'}
  - {name: "Code", url: 'https://github.com/IAAR-Shanghai/MARA,'}
  - {name: "Code", url: 'https://huggingface.co/IAAR-Shanghai/MARA_AGENTS'}
tags: ['Agentic', 'Has Code', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
With the rapid development of Large Language Models (LLMs), aligning these models with human preferences and values is critical to ensuring ethical and safe applications. However, existing alignment techniques such as RLHF or DPO often require direct fine-tuning on LLMs with billions of parameters, resulting in substantial computational costs and inefficiencies. To address this, we propose Micro token-level Accept-Reject Aligning (MARA) approach designed to operate independently of the language models. MARA simplifies the alignment process by decomposing sentence-level preference learning into token-level binary classification, where a compact three-layer fully-connected network determines whether candidate tokens are "Accepted" or "Rejected" as part of the response. Extensive experiments across seven different LLMs and three open-source datasets show that MARA achieves significant improvements in alignment performance while reducing computational costs. The source code and implementation details are publicly available at https://github.com/IAAR-Shanghai/MARA, and the trained models are released at https://huggingface.co/IAAR-Shanghai/MARA_AGENTS.
