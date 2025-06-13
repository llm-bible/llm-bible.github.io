---
layout: publication
title: 'Self-preference Bias In Llm-as-a-judge'
authors: Koki Wataoka, Tsubasa Takahashi, Ryokan Ri
conference: "Arxiv"
year: 2024
bibkey: wataoka2024self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.21819'}
tags: ['RAG', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Ethics and Bias']
---
Automated evaluation leveraging large language models (LLMs), commonly
referred to as LLM evaluators or LLM-as-a-judge, has been widely used in
measuring the performance of dialogue systems. However, the self-preference
bias in LLMs has posed significant risks, including promoting specific styles
or policies intrinsic to the LLMs. Despite the importance of this issue, there
is a lack of established methods to measure the self-preference bias
quantitatively, and its underlying causes are poorly understood. In this paper,
we introduce a novel quantitative metric to measure the self-preference bias.
Our experimental results demonstrate that GPT-4 exhibits a significant degree
of self-preference bias. To explore the causes, we hypothesize that LLMs may
favor outputs that are more familiar to them, as indicated by lower perplexity.
We analyze the relationship between LLM evaluations and the perplexities of
outputs. Our findings reveal that LLMs assign significantly higher evaluations
to outputs with lower perplexity than human evaluators, regardless of whether
the outputs were self-generated. This suggests that the essence of the bias
lies in perplexity and that the self-preference bias exists because LLMs prefer
texts more familiar to them.
