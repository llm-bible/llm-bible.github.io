---
layout: publication
title: 'Answer Generation Through Unified Memories Over Multiple Passages'
authors: Makoto Nakatsuji, Sohei Okui
conference: "Arxiv"
year: 2020
bibkey: nakatsuji2020answer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.13829"}
tags: ['Attention Mechanism', 'Model Architecture']
---
Machine reading comprehension methods that generate answers by referring to
multiple passages for a question have gained much attention in AI and NLP
communities. The current methods, however, do not investigate the relationships
among multiple passages in the answer generation process, even though topics
correlated among the passages may be answer candidates. Our method, called
neural answer Generation through Unified Memories over Multiple Passages
(GUM-MP), solves this problem as follows. First, it determines which tokens in
the passages are matched to the question. In particular, it investigates
matches between tokens in positive passages, which are assigned to the
question, and those in negative passages, which are not related to the
question. Next, it determines which tokens in the passage are matched to other
passages assigned to the same question and at the same time it investigates the
topics in which they are matched. Finally, it encodes the token sequences with
the above two matching results into unified memories in the passage encoders
and learns the answer sequence by using an encoder-decoder with a
multiple-pointer-generator mechanism. As a result, GUM-MP can generate answers
by pointing to important tokens present across passages. Evaluations indicate
that GUM-MP generates much more accurate results than the current models do.
