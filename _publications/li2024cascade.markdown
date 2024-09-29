---
layout: publication
title: Cascade Reward Sampling For Efficient Decoding45;time Alignment
authors: Li Bolian, Wang Yifan, Grama Ananth, Zhang Ruqi
conference: "Arxiv"
year: 2024
bibkey: li2024cascade
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16306"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning']
---
Aligning large language models (LLMs) with human preferences is critical for their deployment. Recently decoding45;time alignment has emerged as an effective plug45;and45;play technique that requires no fine45;tuning of model parameters. However generating text that achieves both high reward and high likelihood remains a significant challenge. Existing methods often fail to generate high45;reward text or incur substantial computational costs. In this paper we propose Cascade Reward Sampling (CARDS) to address both issues guaranteeing the generation of high45;reward and high45;likelihood text with significantly low costs. Based on our analysis of reward models (RMs) on incomplete text and our observation that high45;reward prefixes induce high45;reward complete text we use rejection sampling to iteratively generate small semantic segments to form such prefixes. The segment length is dynamically determined by the predictive uncertainty of LLMs. This strategy guarantees desirable prefixes for subsequent generations and significantly reduces wasteful token re45;generations and the number of reward model scoring. Our experiments demonstrate substantial gains in both generation efficiency and alignment ratings compared to the baselines achieving five times faster text generation and 9937; win45;ties in GPT45;4/Claude45;3 helpfulness evaluation.
