---
layout: publication
title: 'How Does Pretraining Improve Discourse-aware Translation?'
authors: Zhihong Huang, Longyue Wang, Siyou Liu, Derek F. Wong
conference: "Arxiv"
year: 2023
bibkey: huang2023how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19847"}
tags: ['Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'SLT']
---
Pretrained language models (PLMs) have produced substantial improvements in
discourse-aware neural machine translation (NMT), for example, improved
coherence in spoken language translation. However, the underlying reasons for
their strong performance have not been well explained. To bridge this gap, we
introduce a probing task to interpret the ability of PLMs to capture discourse
relation knowledge. We validate three state-of-the-art PLMs across encoder-,
decoder-, and encoder-decoder-based models. The analysis shows that (1) the
ability of PLMs on discourse modelling varies from architecture and layer; (2)
discourse elements in a text lead to different learning difficulties for PLMs.
Besides, we investigate the effects of different PLMs on spoken language
translation. Through experiments on IWSLT2017 Chinese-English dataset, we
empirically reveal that NMT models initialized from different layers of PLMs
exhibit the same trends with the probing task. Our findings are instructive to
understand how and when discourse knowledge in PLMs should work for downstream
tasks.
