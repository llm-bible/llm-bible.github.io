---
layout: publication
title: 'Paraphrase Generation As Zero-shot Multilingual Translation: Disentangling
  Semantic Similarity From Lexical And Syntactic Diversity'
authors: Brian Thompson, Matt Post
conference: Arxiv
year: 2020
citations: 28
bibkey: thompson2020paraphrase
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.04935'}]
tags: [RAG]
---
Recent work has shown that a multilingual neural machine translation (NMT)
model can be used to judge how well a sentence paraphrases another sentence in
the same language (Thompson and Post, 2020); however, attempting to generate
paraphrases from such a model using standard beam search produces trivial
copies or near copies. We introduce a simple paraphrase generation algorithm
which discourages the production of n-grams that are present in the input. Our
approach enables paraphrase generation in many languages from a single
multilingual NMT model. Furthermore, the amount of lexical diversity between
the input and output can be controlled at generation time. We conduct a human
evaluation to compare our method to a paraphraser trained on the large English
synthetic paraphrase database ParaBank 2 (Hu et al., 2019c) and find that our
method produces paraphrases that better preserve meaning and are more
gramatical, for the same level of lexical diversity. Additional smaller human
assessments demonstrate our approach also works in two non-English languages.