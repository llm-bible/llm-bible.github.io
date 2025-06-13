---
layout: publication
title: 'Multimodal Contrastive In-context Learning'
authors: Yosuke Miyanishi, Minh Le Nguyen
conference: "Arxiv"
year: 2024
bibkey: miyanishi2024multimodal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.12959'}
tags: ['Tools', 'Prompting', 'Multimodal Models', 'Reinforcement Learning', 'Ethics and Bias', 'In-Context Learning', 'Pretraining Methods']
---
The rapid growth of Large Language Models (LLMs) usage has highlighted the
importance of gradient-free in-context learning (ICL). However, interpreting
their inner workings remains challenging. This paper introduces a novel
multimodal contrastive in-context learning framework to enhance our
understanding of ICL in LLMs. First, we present a contrastive learning-based
interpretation of ICL in real-world settings, marking the distance of the
key-value representation as the differentiator in ICL. Second, we develop an
analytical framework to address biases in multimodal input formatting for
real-world datasets. We demonstrate the effectiveness of ICL examples where
baseline performance is poor, even when they are represented in unseen formats.
Lastly, we propose an on-the-fly approach for ICL (Anchored-by-Text ICL) that
demonstrates effectiveness in detecting hateful memes, a task where typical ICL
struggles due to resource limitations. Extensive experiments on multimodal
datasets reveal that our approach significantly improves ICL performance across
various scenarios, such as challenging tasks and resource-constrained
environments. Moreover, it provides valuable insights into the mechanisms of
in-context learning in LLMs. Our findings have important implications for
developing more interpretable, efficient, and robust multimodal AI systems,
especially in challenging tasks and resource-constrained environments.
