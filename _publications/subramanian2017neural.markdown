---
layout: publication
title: Neural Models For Key Phrase Detection And Question Generation
authors: Sandeep Subramanian et al.
conference: Arxiv
year: 2017
citations: 34
bibkey: subramanian2017neural
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.04560'}]
tags: [RAG]
---
We propose a two-stage neural model to tackle question generation from
documents. First, our model estimates the probability that word sequences in a
document are ones that a human would pick when selecting candidate answers by
training a neural key-phrase extractor on the answers in a question-answering
corpus. Predicted key phrases then act as target answers and condition a
sequence-to-sequence question-generation model with a copy mechanism.
Empirically, our key-phrase extraction model significantly outperforms an
entity-tagging baseline and existing rule-based approaches. We further
demonstrate that our question generation system formulates fluent, answerable
questions from key phrases. This two-stage system could be used to augment or
generate reading comprehension datasets, which may be leveraged to improve
machine reading systems or in educational settings.