---
layout: publication
title: Attention Sorting Combats Recency Bias In Long Context Language Models
authors: Peysakhovich Alexander, Lerer Adam
conference: "Arxiv"
year: 2023
bibkey: peysakhovich2023attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.01427"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Current language models often fail to incorporate long contexts efficiently during generation. We show that a major contributor to this issue are attention priors that are likely learned during pre-training relevant information located earlier in context is attended to less on average. Yet even when models fail to use the information from a relevant document in their response they still pay preferential attention to that document compared to an irrelevant document at the same position. We leverage this fact to introduce attention sorting perform one step of decoding sort documents by the attention they receive (highest attention going last) repeat the process generate the answer with the newly sorted context. We find that attention sorting improves performance of long context models. Our findings highlight some challenges in using off-the-shelf language models for retrieval augmented generation.
