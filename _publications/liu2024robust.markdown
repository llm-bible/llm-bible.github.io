---
layout: publication
title: 'RRM: Robust Reward Model Training Mitigates Reward Hacking'
authors: Tianqi Liu, Wei Xiong, Jie Ren, Lichang Chen, Junru Wu, Rishabh Joshi, Yang Gao, Jiaming Shen, Zhen Qin, Tianhe Yu, Daniel Sohn, Anastasiia Makarova, Jeremiah Liu, Yuan Liu, Bilal Piot, Abe Ittycheriah, Aviral Kumar, Mohammad Saleh
conference: "Arxiv"
year: 2024
bibkey: liu2024robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13156"}
tags: ['Prompting', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Reward models (RMs) play a pivotal role in aligning large language models
(LLMs) with human preferences. However, traditional RM training, which relies
on response pairs tied to specific prompts, struggles to disentangle
prompt-driven preferences from prompt-independent artifacts, such as response
length and format. In this work, we expose a fundamental limitation of current
RM training methods, where RMs fail to effectively distinguish between
contextual signals and irrelevant artifacts when determining preferences. To
address this, we introduce a causal framework that learns preferences
independent of these artifacts and propose a novel data augmentation technique
designed to eliminate them. Extensive experiments show that our approach
successfully filters out undesirable artifacts, yielding a more robust reward
model (RRM). Our RRM improves the performance of a pairwise reward model
trained on Gemma-2-9b-it, on RewardBench, increasing accuracy from 80.61% to
84.15%. Additionally, we train two DPO policies using both the RM and RRM,
demonstrating that the RRM significantly enhances DPO-aligned policies,
improving MT-Bench scores from 7.27 to 8.31 and length-controlled win-rates in
AlpacaEval-2 from 33.46% to 52.49%.
