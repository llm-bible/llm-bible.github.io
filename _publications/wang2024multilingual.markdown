---
layout: publication
title: 'Multilingual Pretraining Using A Large Corpus Machine-translated From A Single Source Language'
authors: Jiayi Wang, Yao Lu, Maurice Weber, Max Ryabinin, Yihong Chen, Raphael Tang, Pontus Stenetorp
conference: "Arxiv"
year: 2024
bibkey: wang2024multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23956"}
tags: ['Pretraining Methods', 'Training Techniques']
---
English, as a very high-resource language, enables the pretraining of
high-quality large language models (LLMs). The same cannot be said for most
other languages, as leading LLMs still underperform for non-English languages,
likely due to a gap in the quality and diversity of the available multilingual
pretraining corpora. In this work, we find that machine-translated text from a
single high-quality source language can contribute significantly to the
pretraining of multilingual LLMs. We translate FineWeb-Edu, a high-quality
English web dataset, into French, German, and Spanish, resulting in a final
300B-token dataset, which we call TransWeb-Edu, and pretrain a 1.3B-parameter
model, CuatroLLM, from scratch on this dataset. Across five non-English
reasoning tasks, we show that CuatroLLM matches or outperforms state-of-the-art
multilingual models trained using closed data, such as Llama3.2 and Gemma2,
despite using an order of magnitude less data, such as about 6% of the tokens
used for Llama3.2's training. We further demonstrate that with additional
domain-specific pretraining, amounting to less than 1% of TransWeb-Edu,
CuatroLLM surpasses the state of the art in multilingual reasoning. To promote
reproducibility, we release our corpus, models, and training pipeline under
open licenses at hf.co/britllm/CuatroLLM.
