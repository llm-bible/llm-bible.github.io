---
layout: publication
title: 'Falsereject: A Resource For Improving Contextual Safety And Mitigating Over-refusals In Llms Via Structured Reasoning'
authors: Zhehao Zhang, Weijie Xu, Fanyou Wu, Chandan K. Reddy
conference: "Arxiv"
year: 2025
bibkey: zhang2025resource
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.08054'}
tags: ['Agentic', 'Security', 'Training Techniques', 'Tools', 'Prompting', 'Responsible AI']
---
Safety alignment approaches in large language models (LLMs) often lead to the over-refusal of benign queries, significantly diminishing their utility in sensitive scenarios. To address this challenge, we introduce FalseReject, a comprehensive resource containing 16k seemingly toxic queries accompanied by structured responses across 44 safety-related categories. We propose a graph-informed adversarial multi-agent interaction framework to generate diverse and complex prompts, while structuring responses with explicit reasoning to aid models in accurately distinguishing safe from unsafe contexts. FalseReject includes training datasets tailored for both standard instruction-tuned models and reasoning-oriented models, as well as a human-annotated benchmark test set. Our extensive benchmarking on 29 state-of-the-art (SOTA) LLMs reveals persistent over-refusal challenges. Empirical results demonstrate that supervised finetuning with FalseReject substantially reduces unnecessary refusals without compromising overall safety or general language capabilities.
