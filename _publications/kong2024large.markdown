---
layout: publication
title: 'Large Language Model-guided Document Selection'
authors: Xiang Kong, Tom Gunter, Ruoming Pang
conference: "Arxiv"
year: 2024
bibkey: kong2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04638"}
tags: ['Pre-Training', 'Tools', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
Large Language Model (LLM) pre-training exhausts an ever growing compute
budget, yet recent research has demonstrated that careful document selection
enables comparable model quality with only a fraction of the FLOPs. Inspired by
efforts suggesting that domain-specific training document selection is in fact
an interpretable process [Gunasekar et al., 2023], as well as research showing
that instruction-finetuned LLMs are adept zero-shot data labelers [Gilardi et
al.,2023], we explore a promising direction for scalable general-domain
document selection; employing a prompted LLM as a document grader, we distill
quality labels into a classifier model, which is applied at scale to a large,
and already heavily-filtered, web-crawl-derived corpus autonomously. Following
the guidance of this classifier, we drop 75% of the corpus and train LLMs on
the remaining data. Results across multiple benchmarks show that: 1. Filtering
allows us to quality-match a model trained on the full corpus across diverse
benchmarks with at most 70% of the FLOPs, 2. More capable LLM labelers and
classifier models lead to better results that are less sensitive to the
labeler's prompt, 3. In-context learning helps to boost the performance of
less-capable labeling models. In all cases we use open-source datasets, models,
recipes, and evaluation frameworks, so that results can be reproduced by the
community.
