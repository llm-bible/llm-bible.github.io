---
layout: publication
title: 'Lamss: When Large Language Models Meet Self-skepticism'
authors: Yetao Wu, Yihong Wang, Teng Chen, Ningyuan Xi, Qingqing Gu, Hongyang Lei, Luo Ji
conference: "Arxiv"
year: 2024
bibkey: wu2024when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06601"}
  - {name: "Code", url: "https://anonymous.4open.science/r/SM-1E76"}
tags: ['Has Code', 'Uncategorized']
---
Hallucination is a major challenge for large language models (LLMs),
preventing their further application in some fields. The skeptical thinking of
humankind could be useful for LLMs to self-cognition, self-reflection and
alleviate their hallucinations. Inspired by this consideration, we propose a
novel approach called LaMsS, which combines the semantic understanding
capability of LLMs with self-skepticism. By introducing a series of skepticism
tokens and augmenting them into the vocabulary, we conduct both pertaining and
finetuning, which allow the LLM to decode each normal token followed by a
skeptical token, representing different skepticism levels. By calculating the
response skepticism given a query, one can define a new self-aware LLM which is
only willing to answer with relative lower skepticism level than the threshold.
By examining the accuracy, AUC and AP of willingly answering questions, we
demonstrate that LaMsS achieves better performance than baselines on both
multi-choice questions and open-domain question-answering benchmarks, and can
generalize to multi-task and out-of-domain settings. Our study sheds some
lights on the self-skepticism modeling on further artificial intelligence.
Project code and model checkpoints can be found in
https://anonymous.4open.science/r/SM-1E76.
