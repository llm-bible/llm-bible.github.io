---
layout: publication
title: 'Filterllm: Text-to-distribution LLM For Billion-scale Cold-start Recommendation'
authors: Ruochen Liu, Hao Chen, Yuanchen Bei, Zheyu Zhou, Lijia Chen, Qijie Shen, Feiran Huang, Fakhri Karray, Senzhang Wang
conference: "Arxiv"
year: 2025
bibkey: liu2025text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16924"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Large Language Model (LLM)-based cold-start recommendation systems continue
to face significant computational challenges in billion-scale scenarios, as
they follow a "Text-to-Judgment" paradigm. This approach processes user-item
content pairs as input and evaluates each pair iteratively. To maintain
efficiency, existing methods rely on pre-filtering a small candidate pool of
user-item pairs. However, this severely limits the inferential capabilities of
LLMs by reducing their scope to only a few hundred pre-filtered candidates. To
overcome this limitation, we propose a novel "Text-to-Distribution" paradigm,
which predicts an item's interaction probability distribution for the entire
user set in a single inference. Specifically, we present FilterLLM, a framework
that extends the next-word prediction capabilities of LLMs to billion-scale
filtering tasks. FilterLLM first introduces a tailored distribution prediction
and cold-start framework. Next, FilterLLM incorporates an efficient
user-vocabulary structure to train and store the embeddings of billion-scale
users. Finally, we detail the training objectives for both distribution
prediction and user-vocabulary construction. The proposed framework has been
deployed on the Alibaba platform, where it has been serving cold-start
recommendations for two months, processing over one billion cold items.
Extensive experiments demonstrate that FilterLLM significantly outperforms
state-of-the-art methods in cold-start recommendation tasks, achieving over 30
times higher efficiency. Furthermore, an online A/B test validates its
effectiveness in billion-scale recommendation systems.
