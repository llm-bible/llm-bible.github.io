---
layout: publication
title: 'Understanding The Effects Of RLHF On The Quality And Detectability Of Llm-generated Texts'
authors: Beining Xu, Arkaitz Zubiaga
conference: "Arxiv"
year: 2025
bibkey: xu2025understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.17965'}
tags: ['Reinforcement Learning', 'Agentic', 'Security', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated exceptional performance on a
range of downstream NLP tasks by generating text that closely resembles human
writing. However, the ease of achieving this similarity raises concerns from
potential malicious uses at scale by bad actors, as LLM-generated text becomes
increasingly difficult to discern from human text. Although detection methods
have been developed to address this issue, bad actors can further manipulate
LLM-generated texts to make them less detectable. In this work, we study how
further editing texts with Reinforcement Learning from Human Feedback (RLHF),
which aligns model outputs with human preferences, affects (a) the quality of
generated texts for two tasks, and (b) the performance of LLM-generated text
detectors, looking at both training-based and zero-shot detection methods.
Although RLHF improves the quality of LLM-generated texts, we find that it also
tends to produce more detectable, lengthy, and repetitive outputs.
Additionally, we observe that training-based detectors are vulnerable to short
texts and to texts that incorporate code, whereas zero-shot detectors exhibit
greater robustness.
