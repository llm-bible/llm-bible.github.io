---
layout: publication
title: 'Clr-bench: Evaluating Large Language Models In College-level Reasoning'
authors: Junnan Dong, Zijin Hong, Yuanchen Bei, Feiran Huang, Xinrun Wang, Xiao Huang
conference: "Arxiv"
year: 2024
bibkey: dong2024clr
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.17558'}
tags: ['GPT', 'Interpretability and Explainability', 'Model Architecture', 'Merging']
---
Large language models (LLMs) have demonstrated their remarkable performance
across various language understanding tasks. While emerging benchmarks have
been proposed to evaluate LLMs in various domains such as mathematics and
computer science, they merely measure the accuracy in terms of the final
prediction on multi-choice questions. However, it remains insufficient to
verify the essential understanding of LLMs given a chosen choice. To fill this
gap, we present CLR-Bench to comprehensively evaluate the LLMs in complex
college-level reasoning. Specifically, (i) we prioritize 16 challenging college
disciplines in computer science and artificial intelligence. The dataset
contains 5 types of questions, while each question is associated with detailed
explanations from experts. (ii) To quantify a fair evaluation of LLMs'
reasoning ability, we formalize the criteria with two novel metrics.
Q\\(\rightarrow\\)A is utilized to measure the performance of direct answer
prediction, and Q\\(\rightarrow\\)AR effectively considers the joint ability to
answer the question and provide rationale simultaneously. Extensive experiments
are conducted with 40 LLMs over 1,018 discipline-specific questions. The
results demonstrate the key insights that LLMs, even the best closed-source
LLM, i.e., GPT-4 turbo, tend to `guess' the college-level answers. It shows a
dramatic decrease in accuracy from 63.31% Q\\(\rightarrow\\)A to 39.00%
Q\\(\rightarrow\\)AR, indicating an unsatisfactory reasoning ability.
