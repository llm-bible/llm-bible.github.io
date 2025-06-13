---
layout: publication
title: 'Memorization In In-context Learning'
authors: Shahriar Golchin, Mihai Surdeanu, Steven Bethard, Eduardo Blanco, Ellen Riloff
conference: "Arxiv"
year: 2024
bibkey: golchin2024memorization
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.11546'}
tags: ['Few-Shot', 'Prompting', 'In-Context Learning', 'Training Techniques']
---
In-context learning (ICL) has proven to be an effective strategy for
improving the performance of large language models (LLMs) with no additional
training. However, the exact mechanism behind this performance improvement
remains unclear. This study is the first to show how ICL surfaces memorized
training data and to explore the correlation between this memorization and
performance on downstream tasks across various ICL regimes: zero-shot,
few-shot, and many-shot. Our most notable findings include: (1) ICL
significantly surfaces memorization compared to zero-shot learning in most
cases; (2) demonstrations, without their labels, are the most effective element
in surfacing memorization; (3) ICL improves performance when the surfaced
memorization in few-shot regimes reaches a high level (about 40%); and (4)
there is a very strong correlation between performance and memorization in ICL
when it outperforms zero-shot learning. Overall, our study uncovers
memorization as a new factor impacting ICL, raising an important question: to
what extent do LLMs truly generalize from demonstrations in ICL, and how much
of their success is due to memorization?
