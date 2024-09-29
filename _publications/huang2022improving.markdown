---
layout: publication
title: FPT Improving Prompt Tuning Efficiency Via Progressive Training
authors: Huang Yufei, Qin Yujia, Wang Huadong, Yin Yichun, Sun Maosong, Liu Zhiyuan, Liu Qun
conference: "Arxiv"
year: 2022
bibkey: huang2022improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.06840"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Recently prompt tuning (PT) has gained increasing attention as a parameter-efficient way of tuning pre-trained language models (PLMs). Despite extensively reducing the number of tunable parameters and achieving satisfying performance PT is training-inefficient due to its slow convergence. To improve PTs training efficiency we first make some novel observations about the prompt transferability of partial PLMs which are defined by compressing a PLM in depth or width. We observe that the soft prompts learned by different partial PLMs of various sizes are similar in the parameter space implying that these soft prompts could potentially be transferred among partial PLMs. Inspired by these observations we propose Fast Prompt Tuning (FPT) which starts by conducting PT using a small-scale partial PLM and then progressively expands its depth and width until the full-model size. After each expansion we recycle the previously learned soft prompts as initialization for the enlarged partial PLM and then proceed PT. We demonstrate the feasibility of FPT on 5 tasks and show that FPT could save over 3037; training computations while achieving comparable performance.
