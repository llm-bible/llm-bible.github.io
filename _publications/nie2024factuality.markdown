---
layout: publication
title: 'Facttest: Factuality Testing In Large Language Models With Finite-sample And Distribution-free Guarantees'
authors: Fan Nie, Xiaotian Hou, Shuhang Lin, James Zou, Huaxiu Yao, Linjun Zhang
conference: "Arxiv"
year: 2024
bibkey: nie2024factuality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02603"}
tags: ['Tools']
---
The propensity of Large Language Models (LLMs) to generate hallucinations and
non-factual content undermines their reliability in high-stakes domains, where
rigorous control over Type I errors (the conditional probability of incorrectly
classifying hallucinations as truthful content) is essential. Despite its
importance, formal verification of LLM factuality with such guarantees remains
largely unexplored. In this paper, we introduce FactTest, a novel framework
that statistically assesses whether a LLM can confidently provide correct
answers to given questions with high-probability correctness guarantees. We
formulate factuality testing as hypothesis testing problem to enforce an upper
bound of Type I errors at user-specified significance levels. Notably, we prove
that our framework also ensures strong Type II error control under mild
conditions and can be extended to maintain its effectiveness when covariate
shifts exist. Our approach is distribution-free and works for any number of
human-annotated samples. It is model-agnostic and applies to any black-box or
white-box LM. Extensive experiments on question-answering (QA) and
multiple-choice benchmarks demonstrate that FactTest effectively detects
hallucinations and improves the model's ability to abstain from answering
unknown questions, leading to an over 40% accuracy improvement.
