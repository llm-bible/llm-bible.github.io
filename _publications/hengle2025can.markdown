---
layout: publication
title: 'Can Llms Reason Over Extended Multilingual Contexts? Towards Long-context Evaluation Beyond Retrieval And Haystacks'
authors: Amey Hengle, Prasoon Bajpai, Soham Dan, Tanmoy Chakraborty
conference: "Arxiv"
year: 2025
bibkey: hengle2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.12845'}
tags: ['Reinforcement Learning', 'Training Techniques']
---
Existing multilingual long-context benchmarks, often based on the popular
needle-in-a-haystack test, primarily evaluate a model's ability to locate
specific information buried within irrelevant texts. However, such a
retrieval-centric approach is myopic and inherently limited, as successful
recall alone does not indicate a model's capacity to reason over extended
contexts. Moreover, these benchmarks are susceptible to data leakage,
short-circuiting, and risk making the evaluation a priori identifiable. To
address these limitations, we introduce MLRBench, a new synthetic benchmark for
multilingual long-context reasoning. Unlike existing benchmarks, MLRBench goes
beyond surface-level retrieval by including tasks that assess multi-hop
inference, aggregation, and epistemic reasoning. Spanning seven languages,
MLRBench is designed to be parallel, resistant to leakage, and scalable to
arbitrary context lengths. Our extensive experiments with an open-weight large
language model (LLM) reveal a pronounced gap between high- and low-resource
languages, particularly for tasks requiring the model to aggregate multiple
facts or predict the absence of information. We also find that, in multilingual
settings, LLMs effectively utilize less than 30% of their claimed context
length. Although off-the-shelf Retrieval Augmented Generation helps alleviate
this to a certain extent, it does not solve the long-context problem. We
open-source MLRBench to enable future research in improved evaluation and
training of multilingual LLMs.
