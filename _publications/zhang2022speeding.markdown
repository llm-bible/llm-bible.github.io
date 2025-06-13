---
layout: publication
title: 'Gateformer: Speeding Up News Feed Recommendation With Input Gated Transformers'
authors: Peitian Zhang, Zheng Liu
conference: "Arxiv"
year: 2022
bibkey: zhang2022speeding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.04406"}
tags: ['Transformer', 'Efficiency and Optimization', 'Interpretability and Explainability', 'Model Architecture', 'Interpretability', 'Pretraining Methods']
---
News feed recommendation is an important web service. In recent years,
pre-trained language models (PLMs) have been intensively applied to improve the
recommendation quality. However, the utilization of these deep models is
limited in many aspects, such as lack of explainability and being incompatible
with the existing inverted index systems. Above all, the PLMs based
recommenders are inefficient, as the encoding of user-side information will
take huge computation costs. Although the computation can be accelerated with
efficient transformers or distilled PLMs, it is still not enough to make timely
recommendations for the active users, who are associated with super long news
browsing histories.
  In this work, we tackle the efficient news recommendation problem from a
distinctive perspective. Instead of relying on the entire input (i.e., the
collection of news articles a user ever browsed), we argue that the user's
interest can be fully captured merely with those representative keywords.
Motivated by this, we propose GateFormer, where the input data is gated before
feeding into transformers. The gating module is made personalized, lightweight
and end-to-end learnable, such that it may perform accurate and efficient
filtering of informative user input. GateFormer achieves highly impressive
performances in experiments, where it notably outperforms the existing
acceleration approaches in both accuracy and efficiency. We also surprisingly
find that even with over 10-fold compression of the original input, GateFormer
is still able to maintain on-par performances with the SOTA methods.
