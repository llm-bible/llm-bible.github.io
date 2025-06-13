---
layout: publication
title: 'Small Language Models Also Work With Small Vocabularies: Probing The Linguistic Abilities Of Grapheme- And Phoneme-based Baby Llamas'
authors: Bastian Bunzeck, Daniel Duran, Leonie Schade, Sina Zarrieß
conference: "Arxiv"
year: 2024
bibkey: bunzeck2024small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01487"}
tags: ['Tokenization', 'Model Architecture']
---
Recent work investigates whether LMs learn human-like linguistic
generalizations and representations from developmentally plausible amounts of
data. Yet, the basic linguistic units processed in these LMs are determined by
subword-based tokenization, which limits their validity as models of learning
at and below the word level. In this paper, we explore the potential of
tokenization-free, phoneme- and grapheme-based language models. We demonstrate
that small models based on the Llama architecture can achieve strong linguistic
performance on standard syntactic and novel lexical/phonetic benchmarks when
trained with character-level vocabularies. We further show that phoneme-based
models almost match grapheme-based models in standard tasks and novel
evaluations. Our findings suggest a promising direction for creating more
linguistically plausible language models that are better suited for
computational studies of language acquisition and processing.
