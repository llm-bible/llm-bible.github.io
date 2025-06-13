---
layout: publication
title: 'Benchmarking And Improving Generator-validator Consistency Of Language Models'
authors: Xiang Lisa Li, Vaishnavi Shrivastava, Siyan Li, Tatsunori Hashimoto, Percy Liang
conference: "Arxiv"
year: 2023
bibkey: li2023benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.01846'}
tags: ['Training Techniques', 'GPT', 'Tools', 'Fine-Tuning', 'Model Architecture', 'Pretraining Methods']
---
As of September 2023, ChatGPT correctly answers "what is 7+8" with 15, but
when asked "7+8=15, True or False" it responds with "False". This inconsistency
between generating and validating an answer is prevalent in language models
(LMs) and erodes trust. In this paper, we propose a framework for measuring the
consistency between generation and validation (which we call
generator-validator consistency, or GV-consistency), finding that even GPT-4, a
state-of-the-art LM, is GV-consistent only 76% of the time. To improve the
consistency of LMs, we propose to finetune on the filtered generator and
validator responses that are GV-consistent, and call this approach consistency
fine-tuning. We find that this approach improves GV-consistency of Alpaca-30B
from 60% to 93%, and the improvement extrapolates to unseen tasks and domains
(e.g., GV-consistency for positive style transfers extrapolates to unseen
styles like humor). In addition to improving consistency, consistency
fine-tuning improves both generator quality and validator accuracy without
using any labeled data. Evaluated across 6 tasks, including math questions,
knowledge-intensive QA, and instruction following, our method improves the
generator quality by 16% and the validator accuracy by 6.3% across all tasks.
