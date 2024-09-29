---
layout: publication
title: The Evolved Transformer
authors: So David R., Liang Chen, Le Quoc V.
conference: "Arxiv"
year: 2019
bibkey: so2019evolved
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1901.11117"}
tags: ['Model Architecture', 'Pretraining Methods', 'Transformer']
---
Recent works have highlighted the strength of the Transformer architecture on sequence tasks while at the same time neural architecture search (NAS) has begun to outperform human45;designed models. Our goal is to apply NAS to search for a better alternative to the Transformer. We first construct a large search space inspired by the recent advances in feed45;forward sequence models and then run evolutionary architecture search with warm starting by seeding our initial population with the Transformer. To directly search on the computationally expensive WMT 2014 English45;German translation task we develop the Progressive Dynamic Hurdles method which allows us to dynamically allocate more resources to more promising candidate models. The architecture found in our experiments 45;45; the Evolved Transformer 45;45; demonstrates consistent improvement over the Transformer on four well45;established language tasks WMT 2014 English45;German WMT 2014 English45;French WMT 2014 English45;Czech and LM1B. At a big model size the Evolved Transformer establishes a new state45;of45;the45;art BLEU score of 29.8 on WMT14 English45;German; at smaller sizes it achieves the same quality as the original big Transformer with 37.637; less parameters and outperforms the Transformer by 0.7 BLEU at a mobile45;friendly model size of 7M parameters.
