---
layout: publication
title: Continuous Decomposition Of Granularity For Neural Paraphrase Generation
authors: Gu Xiaodong, Zhang Zhaowei, Lee Sang-woo, Yoo Kang Min, Ha Jung-woo
conference: "Arxiv"
year: 2022
bibkey: gu2022continuous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2209.01765"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
While Transformers have had significant success in paragraph generation they treat sentences as linear sequences of tokens and often neglect their hierarchical information. Prior work has shown that decomposing the levels of granularity~(e.g. word phrase or sentence) for input tokens has produced substantial improvements suggesting the possibility of enhancing Transformers via more fine45;grained modeling of granularity. In this work we propose a continuous decomposition of granularity for neural paraphrase generation (C45;DNPG). In order to efficiently incorporate granularity into sentence encoding C45;DNPG introduces a granularity45;aware attention (GA45;Attention) mechanism which extends the multi45;head self45;attention with 1) a granularity head that automatically infers the hierarchical structure of a sentence by neurally estimating the granularity level of each input token; and 2) two novel attention masks namely granularity resonance and granularity scope to efficiently encode granularity into attention. Experiments on two benchmarks including Quora question pairs and Twitter URLs have shown that C45;DNPG outperforms baseline models by a remarkable margin and achieves state45;of45;the45;art results in terms of many metrics. Qualitative analysis reveals that C45;DNPG indeed captures fine45;grained levels of granularity with effectiveness.
