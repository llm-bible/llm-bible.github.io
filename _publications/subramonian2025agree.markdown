---
layout: publication
title: 'Agree To Disagree? A Meta-evaluation Of LLM Misgendering'
authors: Arjun Subramonian, Vagrant Gautam, Preethi Seshadri, Dietrich Klakow, Kai-wei Chang, Yizhou Sun
conference: "Arxiv"
year: 2025
bibkey: subramonian2025agree
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.17075'}
tags: ['Uncategorized']
---
Numerous methods have been proposed to measure LLM misgendering, including
probability-based evaluations (e.g., automatically with templatic sentences)
and generation-based evaluations (e.g., with automatic heuristics or human
validation). However, it has gone unexamined whether these evaluation methods
have convergent validity, that is, whether their results align. Therefore, we
conduct a systematic meta-evaluation of these methods across three existing
datasets for LLM misgendering. We propose a method to transform each dataset to
enable parallel probability- and generation-based evaluation. Then, by
automatically evaluating a suite of 6 models from 3 families, we find that
these methods can disagree with each other at the instance, dataset, and model
levels, conflicting on 20.2% of evaluation instances. Finally, with a human
evaluation of 2400 LLM generations, we show that misgendering behaviour is
complex and goes far beyond pronouns, which automatic evaluations are not
currently designed to capture, suggesting essential disagreement with human
evaluations. Based on our findings, we provide recommendations for future
evaluations of LLM misgendering. Our results are also more widely relevant, as
they call into question broader methodological conventions in LLM evaluation,
which often assume that different evaluation methods agree.
