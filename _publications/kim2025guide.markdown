---
layout: publication
title: 'Guide-cot: Goal-driven And User-informed Dynamic Estimation For Pedestrian Trajectory Using Chain-of-thought'
authors: Sungsik Kim, Janghyun Baek, Jinkyu Kim, Jaekoo Lee
conference: "Arxiv"
year: 2025
bibkey: kim2025guide
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06832"}
  - {name: "Code", url: "https://github.com/ai-kmu/GUIDE-CoT"}
tags: ['Prompting', 'Has Code']
---
While Large Language Models (LLMs) have recently shown impressive results in
reasoning tasks, their application to pedestrian trajectory prediction remains
challenging due to two key limitations: insufficient use of visual information
and the difficulty of predicting entire trajectories. To address these
challenges, we propose Goal-driven and User-Informed Dynamic Estimation for
pedestrian trajectory using Chain-of-Thought (GUIDE-CoT). Our approach
integrates two innovative modules: (1) a goal-oriented visual prompt, which
enhances goal prediction accuracy combining visual prompts with a pretrained
visual encoder, and (2) a chain-of-thought (CoT) LLM for trajectory generation,
which generates realistic trajectories toward the predicted goal. Moreover, our
method introduces controllable trajectory generation, allowing for flexible and
user-guided modifications to the predicted paths. Through extensive experiments
on the ETH/UCY benchmark datasets, our method achieves state-of-the-art
performance, delivering both high accuracy and greater adaptability in
pedestrian trajectory prediction. Our code is publicly available at
https://github.com/ai-kmu/GUIDE-CoT.
