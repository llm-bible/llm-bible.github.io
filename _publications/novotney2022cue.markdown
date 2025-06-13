---
layout: publication
title: 'CUE Vectors: Modular Training Of Language Models Conditioned On Diverse Contextual Signals'
authors: Scott Novotney, Sreeparna Mukherjee, Zeeshan Ahmed, Andreas Stolcke
conference: "Findings of ACL 2022 pp. 3368-3379"
year: 2022
bibkey: novotney2022cue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.08774"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods', 'BERT', 'Transformer', 'ACL']
---
We propose a framework to modularize the training of neural language models
that use diverse forms of sentence-external context (including metadata) by
eliminating the need to jointly train sentence-external and within-sentence
encoders. Our approach, contextual universal embeddings (CUE), trains LMs on
one set of context, such as date and author, and adapts to novel metadata
types, such as article title, or previous sentence. The model consists of a
pretrained neural sentence LM, a BERT-based context encoder, and a masked
transformer decoder that estimates LM probabilities using sentence-internal and
sentence-external information. When context or metadata are unavailable, our
model learns to combine contextual and sentence-internal information using
noisy oracle unigram embeddings as a proxy. Real contextual information can be
introduced later and used to adapt a small number of parameters that map
contextual data into the decoder's embedding space. We validate the CUE
framework on a NYTimes text corpus with multiple metadata types, for which the
LM perplexity can be lowered from 36.6 to 27.4 by conditioning on context.
Bootstrapping a contextual LM with only a subset of the context/metadata during
training retains 85% of the achievable gain. Training the model initially with
proxy context retains 67% of the perplexity gain after adapting to real
context. Furthermore, we can swap one type of pretrained sentence LM for
another without retraining the context encoders, by only adapting the decoder
model. Overall, we obtain a modular framework that allows incremental, scalable
training of context-enhanced LMs.
