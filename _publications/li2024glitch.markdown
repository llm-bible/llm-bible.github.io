---
layout: publication
title: 'Glitch Tokens In Large Language Models: Categorization Taxonomy And Effective Detection'
authors: Li Yuxi, Liu Yi, Deng Gelei, Zhang Ying, Song Wenjia, Shi Ling, Wang Kailong, Li Yuekang, Liu Yang, Wang Haoyu
conference: "Arxiv"
year: 2024
bibkey: li2024glitch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09894"}
tags: ['Pretraining Methods', 'Survey Paper', 'Tokenization']
---
With the expanding application of Large Language Models (LLMs) in various domains it becomes imperative to comprehensively investigate their unforeseen behaviors and consequent outcomes. In this study we introduce and systematically explore the phenomenon of glitch tokens which are anomalous tokens produced by established tokenizers and could potentially compromise the models quality of response. Specifically we experiment on seven top popular LLMs utilizing three distinct tokenizers and involving a totally of 182517 tokens. We present categorizations of the identified glitch tokens and symptoms exhibited by LLMs when interacting with glitch tokens. Based on our observation that glitch tokens tend to cluster in the embedding space we propose GlitchHunter a novel iterative clustering-based technique for efficient glitch token detection. The evaluation shows that our approach notably outperforms three baseline methods on eight open-source LLMs. To the best of our knowledge we present the first comprehensive study on glitch tokens. Our new detection further provides valuable insights into mitigating tokenization-related errors in LLMs.
