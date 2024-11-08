---
layout: publication
title: 'Large Language Models Can Learn Rules'
authors: Zhu Zhaocheng, Xue Yuan, Chen Xinyun, Zhou Denny, Tang Jian, Schuurmans Dale, Dai Hanjun
conference: "Arxiv"
year: 2023
bibkey: zhu2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07064"}
tags: ['Prompting', 'Tools', 'Training Techniques']
---
When prompted with a few examples and intermediate steps, large language
models (LLMs) have demonstrated impressive performance in various reasoning
tasks. However, prompting methods that rely on implicit knowledge in an LLM
often generate incorrect answers when the implicit knowledge is wrong or
inconsistent with the task. To tackle this problem, we present
Hypotheses-to-Theories (HtT), a framework that learns a rule library for
reasoning with LLMs. HtT contains two stages, an induction stage and a
deduction stage. In the induction stage, an LLM is first asked to generate and
verify rules over a set of training examples. Rules that appear and lead to
correct answers sufficiently often are collected to form a rule library. In the
deduction stage, the LLM is then prompted to employ the learned rule library to
perform reasoning to answer test questions. Experiments on relational
reasoning, numerical reasoning and concept learning problems show that HtT
improves existing prompting methods, with an absolute gain of 10-30% in
accuracy. The learned rules are also transferable to different models and to
different forms of the same problem.
