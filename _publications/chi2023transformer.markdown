---
layout: publication
title: 'Transformer Working Memory Enables Regular Language Reasoning And Natural Language Length Extrapolation'
authors: Ta-chung Chi, Ting-han Fan, Alexander I. Rudnicky, Peter J. Ramadge
conference: "Arxiv"
year: 2023
bibkey: chi2023transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03796"}
tags: ['Model Architecture', 'GPT', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Unlike recurrent models, conventional wisdom has it that Transformers cannot
perfectly model regular languages. Inspired by the notion of working memory, we
propose a new Transformer variant named RegularGPT. With its novel combination
of Weight-Sharing, Adaptive-Depth, and Sliding-Dilated-Attention, RegularGPT
constructs working memory along the depth dimension, thereby enabling efficient
and successful modeling of regular languages such as PARITY. We further test
RegularGPT on the task of natural language length extrapolation and
surprisingly find that it rediscovers the local windowed attention effect
deemed necessary in prior work for length extrapolation.
