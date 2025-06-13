---
layout: publication
title: 'Refutebench 2.0 -- Agentic Benchmark For Dynamic Evaluation Of LLM Responses To Refutation Instruction'
authors: Jianhao Yan, Yun Luo, Yue Zhang
conference: "Arxiv"
year: 2025
bibkey: yan2025refutebench
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18308'}
  - {name: "Code", url: 'https://github.com/ElliottYan/RefuteBench-2.0'}
tags: ['Attention Mechanism', 'Agentic', 'Has Code', 'RAG', 'Model Architecture']
---
In the multi-turn interaction schema, large language models (LLMs) can
leverage user feedback to enhance the quality and relevance of their responses.
However, evaluating an LLM's ability to incorporate user refutation feedback is
crucial yet challenging. In this study, we introduce RefuteBench 2.0, which
significantly extends the original RefuteBench by incorporating LLM agents as
refuters and evaluators, which allows for flexible and comprehensive
assessment.
  We design both transient and persistent refutation instructions with
different validity periods. Meta-evaluation shows that the LLM-based refuter
could generate more human-like refutations and the evaluators could assign
scores with high correlation with humans. Experimental results of various LLMs
show that current models could effectively satisfy the refutation but fail to
memorize the refutation information. Interestingly, we also observe that the
performance of the initial task decreases as the refutations increase. Analysis
of the attention scores further shows a potential weakness of current LLMs:
they struggle to retain and correctly use previous information during long
context dialogues. https://github.com/ElliottYan/RefuteBench-2.0
