---
layout: publication
title: Continual Learning in Multilingual NMT via Language-Specific Embeddings
authors: Berard Alexandre
conference: "Arxiv"
year: 2021
bibkey: berard2021continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.10478"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
This paper proposes a technique for adding a new source or target language to an existing multilingual NMT model without re-training it on the initial set of languages. It consists in replacing the shared vocabulary with a small language-specific vocabulary and fine-tuning the new embeddings on the new languages parallel data. Some additional language-specific components may be trained to improve performance (e.g. Transformer layers or adapter modules). Because the parameters of the original model are not modified its performance on the initial languages does not degrade. We show on two sets of experiments (small-scale on TED Talks and large-scale on ParaCrawl) that this approach performs as well or better as the more costly alternatives; and that it has excellent zero-shot performance training on English-centric data is enough to translate between the new language and any of the initial languages.
