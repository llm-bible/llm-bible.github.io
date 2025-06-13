---
layout: publication
title: 'Copy Mechanism And Tailored Training For Character-based Data-to-text Generation'
authors: Marco Roberti, Giovanni Bonetta, Rossella Cancelliere, Patrick Gallinari
conference: "Arxiv"
year: 2019
bibkey: roberti2019copy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1904.11838"}
tags: ['Fine-Tuning', 'Transformer', 'Applications', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Tokenization', 'Attention Mechanism']
---
In the last few years, many different methods have been focusing on using
deep recurrent neural networks for natural language generation. The most widely
used sequence-to-sequence neural methods are word-based: as such, they need a
pre-processing step called delexicalization (conversely, relexicalization) to
deal with uncommon or unknown words. These forms of processing, however, give
rise to models that depend on the vocabulary used and are not completely
neural.
  In this work, we present an end-to-end sequence-to-sequence model with
attention mechanism which reads and generates at a character level, no longer
requiring delexicalization, tokenization, nor even lowercasing. Moreover, since
characters constitute the common "building blocks" of every text, it also
allows a more general approach to text generation, enabling the possibility to
exploit transfer learning for training. These skills are obtained thanks to two
major features: (i) the possibility to alternate between the standard
generation mechanism and a copy one, which allows to directly copy input facts
to produce outputs, and (ii) the use of an original training pipeline that
further improves the quality of the generated texts.
  We also introduce a new dataset called E2E+, designed to highlight the
copying capabilities of character-based models, that is a modified version of
the well-known E2E dataset used in the E2E Challenge. We tested our model
according to five broadly accepted metrics (including the widely used BLEU),
showing that it yields competitive performance with respect to both
character-based and word-based approaches.
