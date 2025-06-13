---
layout: publication
title: 'Attention-guided Self-reflection For Zero-shot Hallucination Detection In Large Language Models'
authors: Qiang Liu, Xinlong Chen, Yue Ding, Shizhen Xu, Shu Wu, Liang Wang
conference: "Arxiv"
year: 2025
bibkey: liu2025attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.09997"}
tags: ['Model Architecture', 'Attention Mechanism']
---
Hallucination has emerged as a significant barrier to the effective
application of Large Language Models (LLMs). In this work, we introduce a novel
Attention-Guided SElf-Reflection (AGSER) approach for zero-shot hallucination
detection in LLMs. The AGSER method utilizes attention contributions to
categorize the input query into attentive and non-attentive queries. Each query
is then processed separately through the LLMs, allowing us to compute
consistency scores between the generated responses and the original answer. The
difference between the two consistency scores serves as a hallucination
estimator. In addition to its efficacy in detecting hallucinations, AGSER
notably reduces computational overhead, requiring only three passes through the
LLM and utilizing two sets of tokens. We have conducted extensive experiments
with four widely-used LLMs across three different hallucination benchmarks,
demonstrating that our approach significantly outperforms existing methods in
zero-shot hallucination detection.
