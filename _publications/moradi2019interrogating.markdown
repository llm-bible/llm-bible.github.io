---
layout: publication
title: 'Interrogating The Explanatory Power Of Attention In Neural Machine Translation'
authors: Pooya Moradi, Nishant Kambhatla, Anoop Sarkar
conference: "Arxiv"
year: 2019
bibkey: moradi2019interrogating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.00139"}
tags: ['Transformer', 'Attention Mechanism', 'Model Architecture', 'Applications']
---
Attention models have become a crucial component in neural machine
translation (NMT). They are often implicitly or explicitly used to justify the
model's decision in generating a specific token but it has not yet been
rigorously established to what extent attention is a reliable source of
information in NMT. To evaluate the explanatory power of attention for NMT, we
examine the possibility of yielding the same prediction but with counterfactual
attention models that modify crucial aspects of the trained attention model.
Using these counterfactual attention mechanisms we assess the extent to which
they still preserve the generation of function and content words in the
translation process. Compared to a state of the art attention model, our
counterfactual attention models produce 68% of function words and 21% of
content words in our German-English dataset. Our experiments demonstrate that
attention models by themselves cannot reliably explain the decisions made by a
NMT model.
