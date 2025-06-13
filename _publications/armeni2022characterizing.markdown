---
layout: publication
title: 'Characterizing Verbatim Short-term Memory In Neural Language Models'
authors: Kristijan Armeni, Christopher Honey, Tal Linzen
conference: "Arxiv"
year: 2022
bibkey: armeni2022characterizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2210.13569'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
When a language model is trained to predict natural language sequences, its
prediction at each moment depends on a representation of prior context. What
kind of information about the prior context can language models retrieve? We
tested whether language models could retrieve the exact words that occurred
previously in a text. In our paradigm, language models (transformers and an
LSTM) processed English text in which a list of nouns occurred twice. We
operationalized retrieval as the reduction in surprisal from the first to the
second list. We found that the transformers retrieved both the identity and
ordering of nouns from the first list. Further, the transformers' retrieval was
markedly enhanced when they were trained on a larger corpus and with greater
model depth. Lastly, their ability to index prior tokens was dependent on
learned attention patterns. In contrast, the LSTM exhibited less precise
retrieval, which was limited to list-initial tokens and to short intervening
texts. The LSTM's retrieval was not sensitive to the order of nouns and it
improved when the list was semantically coherent. We conclude that transformers
implemented something akin to a working memory system that could flexibly
retrieve individual token representations across arbitrary delays; conversely,
the LSTM maintained a coarser and more rapidly-decaying semantic gist of prior
tokens, weighted toward the earliest items.
