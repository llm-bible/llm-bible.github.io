---
layout: publication
title: 'Copy Is All You Need'
authors: Tian Lan, Deng Cai, Yan Wang, Heyan Huang, Xian-ling Mao
conference: "The Eleventh International Conference on Learning Representations (ICLR 2023)"
year: 2023
bibkey: lan2023copy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.06962'}
  - {name: "Code", url: 'https://github.com/gmftbyGMFTBY/Copyisallyouneed}.'}
tags: ['Has Code', 'Language Modeling', 'Efficiency and Optimization', 'GPT', 'Applications', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
The dominant text generation models compose the output by sequentially
selecting words from a fixed vocabulary. In this paper, we formulate text
generation as progressively copying text segments (e.g., words or phrases) from
an existing text collection. We compute the contextualized representations of
meaningful text segments and index them using efficient vector search toolkits.
The task of text generation is then decomposed into a series of copy-and-paste
operations: at each time step, we seek suitable text spans from the text
collection rather than selecting from a standalone vocabulary. Experiments on
the standard language modeling benchmark (WikiText-103) show that our approach
achieves better generation quality according to both automatic and human
evaluations. Besides, its inference efficiency is comparable to token-level
autoregressive models thanks to the reduction of decoding steps. We also show
that our approach allows for effective domain adaptation by simply switching to
domain-specific text collection without extra training. Finally, we observe
that our approach attains additional performance gains by simply scaling up to
larger text collections, again without further training.\footnote\{Our source
codes are publicly available at
\url\{https://github.com/gmftbyGMFTBY/Copyisallyouneed\}.\}
