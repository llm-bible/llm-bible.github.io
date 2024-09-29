---
layout: publication
title: Iterative Length-regularized Direct Preference Optimization A Case Study On Improving 7B Language Models To GPT-4 Level
authors: Liu Jie, Zhou Zhanhui, Liu Jiaheng, Bu Xingyuan, Yang Chao, Zhong Han-sen, Ouyang Wanli
conference: "Arxiv"
year: 2024
bibkey: liu2024iterative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11817"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Direct Preference Optimization (DPO) a standard method for aligning language models with human preferences is traditionally applied to offline preferences. Recent studies show that DPO benefits from iterative training with online preferences labeled by a trained reward model. In this work we identify a pitfall of vanilla iterative DPO - improved response quality can lead to increased verbosity. To address this we introduce iterative length-regularized DPO (iLR-DPO) to penalize response length. Our empirical results show that iLR-DPO can enhance a 7B model to perform on par with GPT-4 without increasing verbosity. Specifically our 7B model achieves a 50.537; length-controlled win rate against (texttt)GPT-4 Preview on AlpacaEval 2.0 and excels across standard benchmarks including MT-Bench Arena-Hard and OpenLLM Leaderboard. These results demonstrate the effectiveness of iterative DPO in aligning language models with human feedback.
