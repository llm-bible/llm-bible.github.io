---
layout: publication
title: Few45;shot Class Incremental Learning With Attention45;aware Self45;adaptive Prompt
authors: Liu Chenxi, Wang Zhenyi, Xiong Tianyi, Chen Ruibo, Wu Yihan, Guo Junfeng, Huang Heng
conference: "Arxiv"
year: 2024
bibkey: liu2024few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09857"}
tags: ['Attention Mechanism', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Few45;Shot Class45;Incremental Learning (FSCIL) models aim to incrementally learn new classes with scarce samples while preserving knowledge of old ones. Existing FSCIL methods usually fine45;tune the entire backbone leading to overfitting and hindering the potential to learn new classes. On the other hand recent prompt45;based CIL approaches alleviate forgetting by training prompts with sufficient data in each task. In this work we propose a novel framework named Attention45;aware Self45;adaptive Prompt (ASP). ASP encourages task45;invariant prompts to capture shared knowledge by reducing specific information from the attention aspect. Additionally self45;adaptive task45;specific prompts in ASP provide specific information and transfer knowledge from old classes to new classes with an Information Bottleneck learning objective. In summary ASP prevents overfitting on base task and does not require enormous data in few45;shot incremental tasks. Extensive experiments on three benchmark datasets validate that ASP consistently outperforms state45;of45;the45;art FSCIL and prompt45;based CIL methods in terms of both learning new classes and mitigating forgetting.
