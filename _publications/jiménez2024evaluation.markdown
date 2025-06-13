---
layout: publication
title: 'An Evaluation Of LLM Code Generation Capabilities Through Graded Exercises'
authors: Álvaro Barbero Jiménez
conference: "Arxiv"
year: 2024
bibkey: jiménez2024evaluation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16292"}
tags: ['GPT', 'Survey Paper', 'Applications', 'Ethics and Bias', 'Model Architecture', 'Training Techniques']
---
Large Language Models have shown prominent capabilities in generating
functional code from natural language descriptions. However, a standardized way
to evaluate these capabilities in an objective and unbiased manner is still to
be found. In this paper we review the current evaluation methods available to
this end, and run a new evaluation of the performance of one state-of-the-art
model (GPT4-o-mini) in solving curated coding challenges in 8 programming
languages, obtained from Codewars, a software development community. Our
analysis shows that the chance of success of the model has a positive
correlation with the task difficulty, the popularity of the programming
language being used and the time elapsed since the publication of the
challenge. A further approximate explanatory analysis in terms of high-level
features hints that while 46.6% of the model performance could be attributed to
task difficulty, a 37.4% seems to be related to leakage of the challenge
solutions into the model training set, while the remaining 16% depends on the
programming language. These results suggest that current evaluation
methodologies might be overestimating the actual skill of Large Language Models
for generating functional code.
