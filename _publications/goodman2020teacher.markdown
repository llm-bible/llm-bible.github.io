---
layout: publication
title: Teaforn Teacher45;forcing With N45;grams
authors: Goodman Sebastian, Ding Nan, Soricut Radu
conference: "Arxiv"
year: 2020
bibkey: goodman2020teacher
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.03494"}
tags: ['Applications', 'Ethics And Bias', 'Model Architecture']
---
Sequence generation models trained with teacher45;forcing suffer from issues related to exposure bias and lack of differentiability across timesteps. Our proposed method Teacher45;Forcing with N45;grams (TeaForN) addresses both these problems directly through the use of a stack of N decoders trained to decode along a secondary time axis that allows model parameter updates based on N prediction steps. TeaForN can be used with a wide class of decoder architectures and requires minimal modifications from a standard teacher45;forcing setup. Empirically we show that TeaForN boosts generation quality on one Machine Translation benchmark WMT 2014 English45;French and two News Summarization benchmarks CNN/Dailymail and Gigaword.
