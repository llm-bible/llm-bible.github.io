---
layout: publication
title: 'Fine-tuning Llms For Low-resource Dialect Translation: The Case Of Lebanese'
authors: Silvana Yakhni, Ali Chehab
conference: "Arxiv"
year: 2025
bibkey: yakhni2025fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00114"}
tags: ['Fine-Tuning', 'Training Techniques', 'Prompting', 'Pretraining Methods']
---
This paper examines the effectiveness of Large Language Models (LLMs) in
translating the low-resource Lebanese dialect, focusing on the impact of
culturally authentic data versus larger translated datasets. We compare three
fine-tuning approaches: Basic, contrastive, and grammar-hint tuning, using
open-source Aya23 models. Experiments reveal that models fine-tuned on a
smaller but culturally aware Lebanese dataset (LW) consistently outperform
those trained on larger, non-native data. The best results were achieved
through contrastive fine-tuning paired with contrastive prompting, which
indicates the benefits of exposing translation models to bad examples. In
addition, to ensure authentic evaluation, we introduce LebEval, a new benchmark
derived from native Lebanese content, and compare it to the existing FLoRes
benchmark. Our findings challenge the "More Data is Better" paradigm and
emphasize the crucial role of cultural authenticity in dialectal translation.
We made our datasets and code available on Github.
