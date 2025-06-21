---
layout: publication
title: Improving Transformer Models By Reordering Their Sublayers
authors: Ofir Press, Noah A. Smith, Omer Levy
conference: Arxiv
year: 2019
citations: 25
bibkey: press2019improving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03864'}]
tags: [Transformer, Language Modeling, Fine-Tuning]
---
Multilayer transformer networks consist of interleaved self-attention and
feedforward sublayers. Could ordering the sublayers in a different pattern lead
to better performance? We generate randomly ordered transformers and train them
with the language modeling objective. We observe that some of these models are
able to achieve better performance than the interleaved baseline, and that
those successful variants tend to have more self-attention at the bottom and
more feedforward sublayers at the top. We propose a new transformer pattern
that adheres to this property, the sandwich transformer, and show that it
improves perplexity on multiple word-level and character-level language
modeling benchmarks, at no cost in parameters, memory, or training time.
However, the sandwich reordering pattern does not guarantee performance gains
across every task, as we demonstrate on machine translation models. Instead, we
suggest that further exploration of task-specific sublayer reorderings is
needed in order to unlock additional gains.