---
layout: publication
title: "How Much Do Language Models Copy From Their Training Data? Evaluating Linguistic Novelty In Text Generation Using RAVEN"
authors: Mccoy R. Thomas, Smolensky Paul, Linzen Tal, Gao Jianfeng, Celikyilmaz Asli
conference: "Arxiv"
year: 2021
bibkey: mccoy2021how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.09509"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Current language models can generate high-quality text. Are they simply copying text they have seen before or have they learned generalizable linguistic abstractions To tease apart these possibilities we introduce RAVEN a suite of analyses for assessing the novelty of generated text focusing on sequential structure (n-grams) and syntactic structure. We apply these analyses to four neural language models (an LSTM a Transformer Transformer-XL and GPT-2). For local structure - e.g. individual dependencies - model-generated text is substantially less novel than our baseline of human-generated text from each models test set. For larger-scale structure - e.g. overall sentence structure - model-generated text is as novel or even more novel than the human-generated baseline but models still sometimes copy substantially in some cases duplicating passages over 1000 words long from the training set. We also perform extensive manual analysis showing that GPT-2s novel text is usually well-formed morphologically and syntactically but has reasonably frequent semantic issues (e.g. being self-contradictory).
