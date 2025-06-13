---
layout: publication
title: 'LAMPO: Large Language Models As Preference Machines For Few-shot Ordinal Classification'
authors: Zhen Qin, Junru Wu, Jiaming Shen, Tianqi Liu, Xuanhui Wang
conference: "Arxiv"
year: 2024
bibkey: qin2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03359"}
tags: ['Training Techniques', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'Survey Paper', 'RAG', 'Ethics and Bias', 'Prompting', 'Applications']
---
We introduce LAMPO, a novel paradigm that leverages Large Language Models
(LLMs) for solving few-shot multi-class ordinal classification tasks. Unlike
conventional methods, which concatenate all demonstration examples with the
test instance and prompt LLMs to produce the pointwise prediction, our
framework uses the LLM as a preference machine that makes a relative
comparative decision between the test instance and each demonstration. A
self-supervised method is then introduced to aggregate these binary comparisons
into the final ordinal decision. LAMPO addresses several limitations inherent
in previous methods, including context length constraints, ordering biases, and
challenges associated with absolute point-wise estimation. Extensive
experiments on seven public datasets demonstrate LAMPO's remarkably competitive
performance across a diverse spectrum of applications (e.g., movie review
analysis and hate speech detection). Notably, in certain applications, the
improvement can be substantial, exceeding 20% in an absolute term. Moreover, we
believe LAMPO represents an interesting addition to the non-parametric
application layered on top of LLMs, as it supports black-box LLMs without
necessitating the outputting of LLM's internal states (e.g., embeddings), as
seen in previous approaches.
