---
layout: publication
title: Pretraining On The Test Set Is All You Need
authors: Schaeffer Rylan
conference: "Arxiv"
year: 2023
bibkey: schaeffer2023pretraining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08632"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Inspired by recent work demonstrating the promise of smaller Transformer-based language models pretrained on carefully curated data we supercharge such approaches by investing heavily in curating a novel high quality non-synthetic data mixture based solely on evaluation benchmarks. Using our novel dataset mixture consisting of less than 100 thousand tokens we pretrain a 1 million parameter transformer-based LLM (pronounced fictional) that achieves perfect results across diverse academic benchmarks strictly outperforming all known foundation models. also beats power-law scaling and exhibits a never-before-seen grokking-like ability to accurately predict downstream evaluation benchmarks canaries.
