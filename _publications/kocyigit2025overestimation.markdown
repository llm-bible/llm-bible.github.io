---
layout: publication
title: 'Overestimation In LLM Evaluation: A Controlled Large-scale Study On Data Contamination''s Impact On Machine Translation'
authors: Muhammed Yusuf Kocyigit, Eleftheria Briakou, Daniel Deutsch, Jiaming Luo, Colin Cherry, Markus Freitag
conference: "Arxiv"
year: 2025
bibkey: kocyigit2025overestimation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.18771"}
tags: ['Training Techniques', 'Pre-Training', 'Applications']
---
Data contamination -- the accidental consumption of evaluation examples
within the pre-training data -- can undermine the validity of evaluation
benchmarks. In this paper, we present a rigorous analysis of the effects of
contamination on language models at 1B and 8B scales on the machine translation
task. Starting from a carefully decontaminated train-test split, we
systematically introduce contamination at various stages, scales, and data
formats to isolate its effect and measure its impact on performance metrics.
Our experiments reveal that contamination with both source and target
substantially inflates BLEU scores, and this inflation is 2.5 times larger (up
to 30 BLEU points) for 8B compared to 1B models. In contrast, source-only and
target-only contamination generally produce smaller, less consistent
over-estimations. Finally, we study how the temporal distribution and frequency
of contaminated samples influence performance over-estimation across languages
with varying degrees of data resources.
