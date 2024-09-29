---
layout: publication
title: Judgelm Fine45;tuned Large Language Models Are Scalable Judges
authors: Zhu Lianghui, Wang Xinggang, Wang Xinlong
conference: "Arxiv"
year: 2023
bibkey: zhu2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.17631"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
Evaluating Large Language Models (LLMs) in open45;ended scenarios is challenging because existing benchmarks and metrics can not measure them comprehensively. To address this problem we propose to fine45;tune LLMs as scalable judges (JudgeLM) to evaluate LLMs efficiently and effectively in open45;ended benchmarks. We first propose a comprehensive large45;scale high45;quality dataset containing task seeds LLMs45;generated answers and GPT45;445;generated judgments for fine45;tuning high45;performance judges as well as a new benchmark for evaluating the judges. We train JudgeLM at different scales from 7B 13B to 33B parameters and conduct a systematic analysis of its capabilities and behaviors. We then analyze the key biases in fine45;tuning LLM as a judge and consider them as position bias knowledge bias and format bias. To address these issues JudgeLM introduces a bag of techniques including swap augmentation reference support and reference drop which clearly enhance the judges performance. JudgeLM obtains the state45;of45;the45;art judge performance on both the existing PandaLM benchmark and our proposed new benchmark. Our JudgeLM is efficient and the JudgeLM45;7B only needs 3 minutes to judge 5K samples with 8 A100 GPUs. JudgeLM obtains high agreement with the teacher judge achieving an agreement exceeding 9037; that even surpasses human45;to45;human agreement. JudgeLM also demonstrates extended capabilities in being judges of the single answer multimodal models multiple answers and multi45;turn chat.
