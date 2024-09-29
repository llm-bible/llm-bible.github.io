---
layout: publication
title: Efficient Inference For Multilingual Neural Machine Translation
authors: Berard Alexandre, Lee Dain, Clinchant Stéphane, Jung Kweonwoo, Nikoulina Vassilina
conference: "Arxiv"
year: 2021
bibkey: berard2021efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.06679"}
tags: ['Applications', 'Model Architecture', 'Security']
---
Multilingual NMT has become an attractive solution for MT deployment in production. But to match bilingual quality it comes at the cost of larger and slower models. In this work we consider several ways to make multilingual NMT faster at inference without degrading its quality. We experiment with several light decoder architectures in two 20-language multi-parallel settings small-scale on TED Talks and large-scale on ParaCrawl. Our experiments demonstrate that combining a shallow decoder with vocabulary filtering leads to more than twice faster inference with no loss in translation quality. We validate our findings with BLEU and chrF (on 380 language pairs) robustness evaluation and human evaluation.
