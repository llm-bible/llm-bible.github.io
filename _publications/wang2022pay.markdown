---
layout: publication
title: 'Pay Attention To Your Tone: Introducing A New Dataset For Polite Language Rewrite'
authors: Xun Wang, Tao Ge, Allen Mao, Yuki Li, Furu Wei, Si-qing Chen
conference: "Arxiv"
year: 2022
bibkey: wang2022pay
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2212.10190'}
tags: ['Attention Mechanism', 'Training Techniques', 'GPT', 'Model Architecture', 'Survey Paper']
---
We introduce \textsc\{PoliteRewrite\} -- a dataset for polite language rewrite
which is a novel sentence rewrite task. Compared with previous text style
transfer tasks that can be mostly addressed by slight token- or phrase-level
edits, polite language rewrite requires deep understanding and extensive
sentence-level edits over an offensive and impolite sentence to deliver the
same message euphemistically and politely, which is more challenging -- not
only for NLP models but also for human annotators to rewrite with effort. To
alleviate the human effort for efficient annotation, we first propose a novel
annotation paradigm by a collaboration of human annotators and GPT-3.5 to
annotate \textsc\{PoliteRewrite\}. The released dataset has 10K polite sentence
rewrites annotated collaboratively by GPT-3.5 and human, which can be used as
gold standard for training, validation and test; and 100K high-quality polite
sentence rewrites by GPT-3.5 without human review. We wish this work (The
dataset (10K+100K) will be released soon) could contribute to the research on
more challenging sentence rewrite, and provoke more thought in future on
resource annotation paradigm with the help of the large-scaled pretrained
models.
