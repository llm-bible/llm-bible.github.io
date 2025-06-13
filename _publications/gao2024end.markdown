---
layout: publication
title: 'End-to-end Training For Recommendation With Language-based User Profiles'
authors: Zhaolin Gao, Joyce Zhou, Yijia Dai, Thorsten Joachims
conference: "Arxiv"
year: 2024
bibkey: gao2024end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18870"}
  - {name: "Code", url: "https://github.com/ZhaolinGao/LangPTune"}
tags: ['Tools', 'GPT', 'Ethics and Bias', 'Interpretability and Explainability', 'Model Architecture', 'Interpretability', 'Training Techniques', 'RecSys', 'Has Code']
---
There is a growing interest in natural language-based user profiles for
recommender systems, which aims to enhance transparency and scrutability
compared with embedding-based methods. Existing studies primarily generate
these profiles using zero-shot inference from large language models (LLMs), but
their quality remains insufficient, leading to suboptimal recommendation
performance. In this paper, we introduce LangPTune, the first end-to-end
training framework to optimize LLM-generated user profiles. Our method
significantly outperforms zero-shot approaches by explicitly training the LLM
for the recommendation objective. Through extensive evaluations across diverse
training configurations and benchmarks, we demonstrate that LangPTune not only
surpasses zero-shot baselines but can also matches the performance of
state-of-the-art embedding-based methods. Finally, we investigate whether the
training procedure preserves the interpretability of these profiles compared to
zero-shot inference through both GPT-4 simulations and crowdworker user
studies. Implementation of LangPTune can be found at
https://github.com/ZhaolinGao/LangPTune.
