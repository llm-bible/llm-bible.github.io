---
layout: publication
title: 'Banishing LLM Hallucinations Requires Rethinking Generalization'
authors: Johnny Li, Saksham Consul, Eda Zhou, James Wong, Naila Farooqui, Yuxin Ye, Nithyashree Manohar, Zhuxiaona Wei, Tian Wu, Ben Echols, Sharon Zhou, Gregory Diamos
conference: "Arxiv"
year: 2024
bibkey: li2024banishing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.17642'}
tags: ['Training Techniques']
---
Despite their powerful chat, coding, and reasoning abilities, Large Language
Models (LLMs) frequently hallucinate. Conventional wisdom suggests that
hallucinations are a consequence of a balance between creativity and
factuality, which can be mitigated, but not eliminated, by grounding the LLM in
external knowledge sources. Through extensive systematic experiments, we show
that these traditional approaches fail to explain why LLMs hallucinate in
practice. Specifically, we show that LLMs augmented with a massive Mixture of
Memory Experts (MoME) can easily memorize large datasets of random numbers. We
corroborate these experimental findings with a theoretical construction showing
that simple neural networks trained to predict the next token hallucinate when
the training loss is above a threshold as it usually does in practice when
training on internet scale data. We interpret our findings by comparing against
traditional retrieval methods for mitigating hallucinations. We use our
findings to design a first generation model for removing hallucinations --
Lamini-1 -- that stores facts in a massive mixture of millions of memory
experts that are retrieved dynamically.
