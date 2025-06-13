---
layout: publication
title: 'Simulating Weighted Automata Over Sequences And Trees With Transformers'
authors: Michael Rizvi, Maude Lizaire, Clara Lacroce, Guillaume Rabusseau
conference: "Arxiv"
year: 2024
bibkey: rizvi2024simulating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.09728'}
tags: ['Training Techniques', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
Transformers are ubiquitous models in the natural language processing (NLP)
community and have shown impressive empirical successes in the past few years.
However, little is understood about how they reason and the limits of their
computational capabilities. These models do not process data sequentially, and
yet outperform sequential neural models such as RNNs. Recent work has shown
that these models can compactly simulate the sequential reasoning abilities of
deterministic finite automata (DFAs). This leads to the following question: can
transformers simulate the reasoning of more complex finite state machines? In
this work, we show that transformers can simulate weighted finite automata
(WFAs), a class of models which subsumes DFAs, as well as weighted tree
automata (WTA), a generalization of weighted automata to tree structured
inputs. We prove these claims formally and provide upper bounds on the sizes of
the transformer models needed as a function of the number of states the target
automata. Empirically, we perform synthetic experiments showing that
transformers are able to learn these compact solutions via standard
gradient-based training.
