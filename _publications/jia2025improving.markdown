---
layout: publication
title: 'Improving LLM Interpretability And Performance Via Guided Embedding Refinement For Sequential Recommendation'
authors: Nanshan Jia, Chenfei Yuan, Yuhang Wu, Zeyu Zheng
conference: "Arxiv"
year: 2025
bibkey: jia2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11658"}
tags: ['Responsible AI', 'Tools', 'Ethics and Bias', 'Interpretability and Explainability', 'Reinforcement Learning', 'Interpretability', 'Training Techniques']
---
The fast development of Large Language Models (LLMs) offers growing
opportunities to further improve sequential recommendation systems. Yet for
some practitioners, integrating LLMs to their existing base recommendation
systems raises questions about model interpretability, transparency and related
safety. To partly alleviate challenges from these questions, we propose guided
embedding refinement, a method that carries out a guided and interpretable
usage of LLM to enhance the embeddings associated with the base recommendation
system. Instead of directly using LLMs as the backbone of sequential
recommendation systems, we utilize them as auxiliary tools to emulate the sales
logic of recommendation and generate guided embeddings that capture
domain-relevant semantic information on interpretable attributes. Benefiting
from the strong generalization capabilities of the guided embedding, we
construct refined embedding by using the guided embedding and reduced-dimension
version of the base embedding. We then integrate the refined embedding into the
recommendation module for training and inference. A range of numerical
experiments demonstrate that guided embedding is adaptable to various given
existing base embedding models, and generalizes well across different
recommendation tasks. The numerical results show that the refined embedding not
only improves recommendation performance, achieving approximately \\(10%\\) to
\\(50%\\) gains in Mean Reciprocal Rank (MRR), Recall rate, and Normalized
Discounted Cumulative Gain (NDCG), but also enhances interpretability, as
evidenced by case studies.
