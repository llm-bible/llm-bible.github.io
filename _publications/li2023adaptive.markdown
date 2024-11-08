---
layout: publication
title: 'Adaptive Gating In Mixture-of-experts Based Language Models'
authors: Li Jiamin, Su Qiang, Yang Yitao, Jiang Yimin, Wang Cong, Xu Hong
conference: "Arxiv"
year: 2023
bibkey: li2023adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07188"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques']
---
Large language models, such as OpenAI's ChatGPT, have demonstrated
exceptional language understanding capabilities in various NLP tasks. Sparsely
activated mixture-of-experts (MoE) has emerged as a promising solution for
scaling models while maintaining a constant number of computational operations.
Existing MoE model adopts a fixed gating network where each token is computed
by the same number of experts. However, this approach contradicts our intuition
that the tokens in each sequence vary in terms of their linguistic complexity
and, consequently, require different computational costs. Little is discussed
in prior research on the trade-off between computation per token and model
performance. This paper introduces adaptive gating in MoE, a flexible training
strategy that allows tokens to be processed by a variable number of experts
based on expert probability distribution. The proposed framework preserves
sparsity while improving training efficiency. Additionally, curriculum learning
is leveraged to further reduce training time. Extensive experiments on diverse
NLP tasks show that adaptive gating reduces at most 22.5% training time while
maintaining inference quality. Moreover, we conduct a comprehensive analysis of
the routing decisions and present our insights when adaptive gating is used.
