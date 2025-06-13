---
layout: publication
title: 'ANPMI: Assessing The True Comprehension Capabilities Of Llms For Multiple Choice Questions'
authors: Gyeongje Cho, Yeonkyoung So, Jaejin Lee
conference: "Arxiv"
year: 2025
bibkey: cho2025assessing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18798'}
tags: ['Reinforcement Learning', 'Ethics and Bias', 'Prompting', 'Applications']
---
Multiple-choice benchmarks, consisting of various prompts and choices, are
among the most widely used methods to assess a language model's natural
language understanding capability. Given a specific prompt, we typically
compute \\(P(Choice|Prompt)\\) to evaluate how likely a language model is to
generate the correct choice compared to incorrect ones. However, we observe
that performance measured using this approach reflects not only the model's
comprehension of the prompt but also its inherent biases for certain choices
regardless of the prompt. This issue makes it challenging to accurately measure
a model's natural language understanding, as models may select the answer
without fully understanding the prompt. To address this limitation, we propose
a novel metric called ANPMI, which normalizes Pointwise Mutual Information
(PMI) by \\(-log P(Choice)\\). ANPMI provides a more accurate assessment of the
model's natural language understanding by ensuring that it is challenging to
answer a question without properly understanding the prompt.
