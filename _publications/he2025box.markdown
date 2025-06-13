---
layout: publication
title: 'The Box Is In The Pen: Evaluating Commonsense Reasoning In Neural Machine Translation'
authors: Jie He, Tao Wang, Deyi Xiong, Qun Liu
conference: "Arxiv"
year: 2025
bibkey: he2025box
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.03308'}
  - {name: "Code", url: 'https://github.com/tjunlp-lab/CommonMT'}
tags: ['Has Code', 'GPT', 'BERT', 'Applications', 'Model Architecture', 'Reinforcement Learning']
---
Does neural machine translation yield translations that are congenial with
common sense? In this paper, we present a test suite to evaluate the
commonsense reasoning capability of neural machine translation. The test suite
consists of three test sets, covering lexical and contextless/contextual
syntactic ambiguity that requires commonsense knowledge to resolve. We manually
create 1,200 triples, each of which contain a source sentence and two
contrastive translations, involving 7 different common sense types. Language
models pretrained on large-scale corpora, such as BERT, GPT-2, achieve a
commonsense reasoning accuracy of lower than 72% on target translations of this
test suite. We conduct extensive experiments on the test suite to evaluate
commonsense reasoning in neural machine translation and investigate factors
that have impact on this capability. Our experiments and analyses demonstrate
that neural machine translation performs poorly on commonsense reasoning of the
three ambiguity types in terms of both reasoning accuracy (60.1%) and reasoning
consistency (31%). The built commonsense test suite is available at
https://github.com/tjunlp-lab/CommonMT.
