---
layout: publication
title: 'Do Llms Know About Hallucination? An Empirical Investigation Of Llm''s Hidden States'
authors: Hanyu Duan, Yi Yang, Kar Yan Tam
conference: "Arxiv"
year: 2024
bibkey: duan2024do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09733"}
tags: ['Tools']
---
Large Language Models (LLMs) can make up answers that are not real, and this
is known as hallucination. This research aims to see if, how, and to what
extent LLMs are aware of hallucination. More specifically, we check whether and
how an LLM reacts differently in its hidden states when it answers a question
right versus when it hallucinates. To do this, we introduce an experimental
framework which allows examining LLM's hidden states in different hallucination
situations. Building upon this framework, we conduct a series of experiments
with language models in the LLaMA family (Touvron et al., 2023). Our empirical
findings suggest that LLMs react differently when processing a genuine response
versus a fabricated one. We then apply various model interpretation techniques
to help understand and explain the findings better. Moreover, informed by the
empirical observations, we show great potential of using the guidance derived
from LLM's hidden representation space to mitigate hallucination. We believe
this work provides insights into how LLMs produce hallucinated answers and how
to make them occur less often.
