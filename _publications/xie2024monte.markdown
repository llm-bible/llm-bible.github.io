---
layout: publication
title: Monte Carlo Tree Search Boosts Reasoning Via Iterative Preference Learning
authors: Xie Yuxi, Goyal Anirudh, Zheng Wenyue, Kan Min-yen, Lillicrap Timothy P., Kawaguchi Kenji, Shieh Michael
conference: "Arxiv"
year: 2024
bibkey: xie2024monte
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00451"}
  - {name: "Code", url: "https://github.com/YuxiXie/MCTS&#45;DPO"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
We introduce an approach aimed at enhancing the reasoning capabilities of Large Language Models (LLMs) through an iterative preference learning process inspired by the successful strategy employed by AlphaZero. Our work leverages Monte Carlo Tree Search (MCTS) to iteratively collect preference data utilizing its look45;ahead ability to break down instance45;level rewards into more granular step45;level signals. To enhance consistency in intermediate steps we combine outcome validation and stepwise self45;evaluation continually updating the quality assessment of newly generated data. The proposed algorithm employs Direct Preference Optimization (DPO) to update the LLM policy using this newly generated step45;level preference data. Theoretical analysis reveals the importance of using on45;policy sampled data for successful self45;improving. Extensive evaluations on various arithmetic and commonsense reasoning tasks demonstrate remarkable performance improvements over existing models. For instance our approach outperforms the Mistral45;7B Supervised Fine45;Tuning (SFT) baseline on GSM8K MATH and ARC45;C with substantial increases in accuracy to 81.837; (+5.937;) 34.737; (+5.837;) and 76.437; (+15.837;) respectively. Additionally our research delves into the training and inference compute tradeoff providing insights into how our method effectively maximizes performance gains. Our code is publicly available at https://github.com/YuxiXie/MCTS&#45;DPO.
