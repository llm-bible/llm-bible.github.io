---
layout: publication
title: 'Enhancing LLM Reasoning Via Critique Models With Test-time And Training-time Supervision'
authors: Zhiheng Xi, Dingwen Yang, Jixuan Huang, Jiafu Tang, Guanyu Li, Yiwen Ding, Wei He, Boyang Hong, Shihan Do, Wenyu Zhan, Xiao Wang, Rui Zheng, Tao Ji, Xiaowei Shi, Yitao Zhai, Rongxiang Weng, Jingang Wang, Xunliang Cai, Tao Gui, Zuxuan Wu, Qi Zhang, Xipeng Qiu, Xuanjing Huang, Yu-gang Jiang
conference: "Arxiv"
year: 2024
bibkey: xi2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.16579"}
  - {name: "Code", url: "https://mathcritique.github.io/}{https://mathcritique.github.io/"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Training large language models (LLMs) to spend more time thinking and
reflection before responding is crucial for effectively solving complex
reasoning tasks in fields such as science, coding, and mathematics. However,
the effectiveness of mechanisms like self-reflection and self-correction
depends on the model's capacity to accurately assess its own performance, which
can be limited by factors such as initial accuracy, question difficulty, and
the lack of external feedback. In this paper, we delve into a two-player
paradigm that separates the roles of reasoning and critique models, where the
critique model provides step-level feedback to supervise the reasoning (actor)
model during both test-time and train-time. We first propose AutoMathCritique,
an automated and scalable framework for collecting critique data, resulting in
a dataset of \\(76,321\\) responses paired with step-level feedback. Fine-tuning
language models with this dataset enables them to generate natural language
feedback for mathematical reasoning. We demonstrate that the critique models
consistently improve the actor's performance on difficult queries at test-time,
especially when scaling up inference-time computation. Motivated by these
findings, we introduce the critique-based supervision to the actor's
self-training process, and propose a critique-in-the-loop self-improvement
method. Experiments show that the method improves the actor's exploration
efficiency and solution diversity, especially on challenging queries, leading
to a stronger reasoning model. Lastly, we take the preliminary step to explore
training self-talk reasoning models via critique supervision and showcase its
potential. Our code and datasets are at
\href\{https://mathcritique.github.io/\}\{https://mathcritique.github.io/\}.
