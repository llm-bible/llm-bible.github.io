---
layout: publication
title: 'Measuring Semantic Abstraction Of Multilingual NMT With Paraphrase Recognition And Generation Tasks'
authors: Tiedemann Jörg, Scherrer Yves
conference: "Arxiv"
year: 2018
bibkey: tiedemann2018measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1808.06826"}
tags: ['Reinforcement Learning', 'Uncategorized']
---
In this paper, we investigate whether multilingual neural translation models
learn stronger semantic abstractions of sentences than bilingual ones. We test
this hypotheses by measuring the perplexity of such models when applied to
paraphrases of the source language. The intuition is that an encoder produces
better representations if a decoder is capable of recognizing synonymous
sentences in the same language even though the model is never trained for that
task. In our setup, we add 16 different auxiliary languages to a bidirectional
bilingual baseline model (English-French) and test it with in-domain and
out-of-domain paraphrases in English. The results show that the perplexity is
significantly reduced in each of the cases, indicating that meaning can be
grounded in translation. This is further supported by a study on paraphrase
generation that we also include at the end of the paper.
