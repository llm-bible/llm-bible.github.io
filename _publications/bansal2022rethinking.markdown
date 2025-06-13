---
layout: publication
title: 'Rethinking The Role Of Scale For In-context Learning: An Interpretability-based Case Study At 66 Billion Scale'
authors: Hritik Bansal, Karthik Gopalakrishnan, Saket Dingliwal, Sravan Bodapati, Katrin Kirchhoff, Dan Roth
conference: "Arxiv"
year: 2022
bibkey: bansal2022rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.09095"}
tags: ['Arxiv', 'Model Architecture', 'Reinforcement Learning', 'In-Context Learning', 'Interpretability and Explainability', 'Prompting', 'Attention Mechanism']
---
Language models have been shown to perform better with an increase in scale
on a wide variety of tasks via the in-context learning paradigm. In this paper,
we investigate the hypothesis that the ability of a large language model to
in-context learn-perform a task is not uniformly spread across all of its
underlying components. Using a 66 billion parameter language model (OPT-66B)
across a diverse set of 14 downstream tasks, we find this is indeed the case:
\\(\sim\\)70% of attention heads and \\(\sim\\)20% of feed forward networks can be
removed with minimal decline in task performance. We find substantial overlap
in the set of attention heads (un)important for in-context learning across
tasks and number of in-context examples. We also address our hypothesis through
a task-agnostic lens, finding that a small set of attention heads in OPT-66B
score highly on their ability to perform primitive induction operations
associated with in-context learning, namely, prefix matching and copying. These
induction heads overlap with task-specific important heads, reinforcing
arguments by Olsson et al. (arXiv:2209.11895) regarding induction head
generality to more sophisticated behaviors associated with in-context learning.
Overall, our study provides several insights that indicate large language
models may be under-trained for in-context learning and opens up questions on
how to pre-train language models to more effectively perform in-context
learning.
