---
layout: publication
title: 'Novo: Norm Voting Off Hallucinations With Attention Heads In Large Language Models'
authors: Zheng Yi Ho, Siyuan Liang, Sen Zhang, Yibing Zhan, Dacheng Tao
conference: "Arxiv"
year: 2024
bibkey: ho2024norm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08970"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'TACL', 'ACL', 'Interpretability and Explainability', 'Applications', 'Attention Mechanism']
---
Hallucinations in Large Language Models (LLMs) remain a major obstacle,
particularly in high-stakes applications where factual accuracy is critical.
While representation editing and reading methods have made strides in reducing
hallucinations, their heavy reliance on specialised tools and training on
in-domain samples, makes them difficult to scale and prone to overfitting. This
limits their accuracy gains and generalizability to diverse datasets. This
paper presents a lightweight method, Norm Voting (NoVo), which harnesses the
untapped potential of attention head norms to dramatically enhance factual
accuracy in zero-shot multiple-choice questions (MCQs). NoVo begins by
automatically selecting truth-correlated head norms with an efficient,
inference-only algorithm using only 30 random samples, allowing NoVo to
effortlessly scale to diverse datasets. Afterwards, selected head norms are
employed in a simple voting algorithm, which yields significant gains in
prediction accuracy. On TruthfulQA MC1, NoVo surpasses the current
state-of-the-art and all previous methods by an astounding margin -- at least
19 accuracy points. NoVo demonstrates exceptional generalization to 20 diverse
datasets, with significant gains in over 90% of them, far exceeding all
current representation editing and reading methods. NoVo also reveals promising
gains to finetuning strategies and building textual adversarial defence. NoVo's
effectiveness with head norms opens new frontiers in LLM interpretability,
robustness and reliability.
