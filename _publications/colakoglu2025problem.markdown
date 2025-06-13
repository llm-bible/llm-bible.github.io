---
layout: publication
title: 'Problem Solved? Information Extraction Design Space For Layout-rich Documents Using Llms'
authors: Gaye Colakoglu, Gürkan Solmaz, Jonathan Fürst
conference: "Arxiv"
year: 2025
bibkey: colakoglu2025problem
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18179"}
  - {name: "Code", url: "https://github.com/gayecolakoglu/LayIE-LLM"}
tags: ['Prompting', 'Multimodal Models', 'Fine-Tuning', 'Has Code']
---
This paper defines and explores the design space for information extraction
(IE) from layout-rich documents using large language models (LLMs). The three
core challenges of layout-aware IE with LLMs are 1) data structuring, 2) model
engagement, and 3) output refinement. Our study delves into the sub-problems
within these core challenges, such as input representation, chunking,
prompting, and selection of LLMs and multimodal models. It examines the
outcomes of different design choices through a new layout-aware IE test suite,
benchmarking against the state-of-art (SoA) model LayoutLMv3. The results show
that the configuration from one-factor-at-a-time (OFAT) trial achieves
near-optimal results with 14.1 points F1-score gain from the baseline model,
while full factorial exploration yields only a slightly higher 15.1 points gain
at around 36x greater token usage. We demonstrate that well-configured
general-purpose LLMs can match the performance of specialized models, providing
a cost-effective alternative. Our test-suite is freely available at
https://github.com/gayecolakoglu/LayIE-LLM.
