---
layout: publication
title: 'Same Evaluation, More Tokens: On The Effect Of Input Length For Machine Translation Evaluation Using Large Language Models'
authors: Tobias Domhan, Dawei Zhu
conference: "Arxiv"
year: 2025
bibkey: domhan2025same
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.01761"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Accurately evaluating machine-translated text remains a long-standing
challenge, particularly for long documents. Recent work has shown that large
language models (LLMs) can serve as reliable and interpretable sentence-level
translation evaluators via MQM error span annotations. With modern LLMs
supporting larger context windows, a natural question arises: can we feed
entire document translations into an LLM for quality assessment? Ideally,
evaluation should be invariant to text length, producing consistent error spans
regardless of input granularity. However, our analysis shows that text length
significantly impacts evaluation: longer texts lead to fewer error spans and
reduced system ranking accuracy. To address this limitation, we evaluate
several strategies, including granularity-aligned prompting, Focus Sentence
Prompting (FSP), and a fine-tuning approach to better align LLMs with the
evaluation task. The latter two methods largely mitigate this length bias,
making LLMs more reliable for long-form translation evaluation.
