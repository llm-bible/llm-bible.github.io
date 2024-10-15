---
layout: publication
title: 'Uncertainty Aware Learning For Language Model Alignment'
authors: Wang Yikun, Zheng Rui, Ding Liang, Zhang Qi, Lin Dahua, Tao Dacheng
conference: "Arxiv"
year: 2024
bibkey: wang2024uncertainty
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04854"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
As instruction-tuned large language models (LLMs) evolve, aligning pretrained
foundation models presents increasing challenges. Existing alignment
strategies, which typically leverage diverse and high-quality data sources,
often overlook the intrinsic uncertainty of tasks, learning all data samples
equally. This may lead to suboptimal data efficiency and model performance. In
response, we propose uncertainty-aware learning (UAL) to improve the model
alignment of different task scenarios, by introducing the sample uncertainty
(elicited from more capable LLMs). We implement UAL in a simple fashion --
adaptively setting the label smoothing value of training according to the
uncertainty of individual samples. Analysis shows that our UAL indeed
facilitates better token clustering in the feature space, validating our
hypothesis. Extensive experiments on widely used benchmarks demonstrate that
our UAL significantly and consistently outperforms standard supervised
fine-tuning. Notably, LLMs aligned in a mixed scenario have achieved an average
improvement of 10.62% on high-entropy tasks (i.e., AlpacaEval leaderboard),
and 1.81% on complex low-entropy tasks (i.e., MetaMath and GSM8K).
