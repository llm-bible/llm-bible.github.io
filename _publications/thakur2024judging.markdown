---
layout: publication
title: 'Judging The Judges: Evaluating Alignment And Vulnerabilities In Llms-as-judges'
authors: Aman Singh Thakur, Kartik Choudhary, Venkat Srinik Ramayapally, Sankaran Vaidyanathan, Dieuwke Hupkes
conference: "Arxiv"
year: 2024
bibkey: thakur2024judging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.12624'}
tags: ['Ethics and Bias', 'Prompting', 'Tools']
---
Offering a promising solution to the scalability challenges associated with
human evaluation, the LLM-as-a-judge paradigm is rapidly gaining traction as an
approach to evaluating large language models (LLMs). However, there are still
many open questions about the strengths and weaknesses of this paradigm, and
what potential biases it may hold. In this paper, we present a comprehensive
study of the performance of various LLMs acting as judges, focusing on a clean
scenario in which inter-human agreement is high. Investigating thirteen judge
models of different model sizes and families, judging answers of nine different
'examtaker models' - both base and instruction-tuned - we find that only the
best (and largest) models achieve reasonable alignment with humans. However,
they are still quite far behind inter-human agreement and their assigned scores
may still differ with up to 5 points from human-assigned scores. In terms of
their ranking of the nine exam-taker models, instead, also smaller models and
even the lexical metric contains may provide a reasonable signal. Through error
analysis and other studies, we identify vulnerabilities in judge models, such
as their sensitivity to prompt complexity and length, and a tendency toward
leniency. The fact that even the best judges differ from humans in this
comparatively simple setup suggest that caution may be wise when using judges
in more complex setups. Lastly, our research rediscovers the importance of
using alignment metrics beyond simple percent alignment, showing that judges
with high percent agreement can still assign vastly different scores.
