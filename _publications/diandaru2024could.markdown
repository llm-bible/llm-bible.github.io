---
layout: publication
title: Could We Have Had Better Multilingual LLMs If English Was Not the Central Language
authors: Diandaru Ryandito, Susanto Lucky, Tang Zilu, Purwarianti Ayu, Wijaya Derry
conference: "Arxiv"
year: 2024
bibkey: diandaru2024could
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13917"}
tags: ['Applications', 'Arxiv']
---
Large Language Models (LLMs) demonstrate strong machine translation capabilities on languages they are trained on. However the impact of factors beyond training data size on translation performance remains a topic of debate especially concerning languages not directly encountered during training. Our study delves into Llama2s translation capabilities. By modeling a linear relationship between linguistic feature distances and machine translation scores we ask ourselves if there are potentially better central languages for LLMs other than English. Our experiments show that the 7B Llama2 model yields above 10 BLEU when translating into all languages it has seen which rarely happens for languages it has not seen. Most translation improvements into unseen languages come from scaling up the model size rather than instruction tuning or increasing shot count. Furthermore our correlation analysis reveals that syntactic similarity is not the only linguistic factor that strongly correlates with machine translation scores. Interestingly we discovered that under specific circumstances some languages (e.g. Swedish Catalan) despite having significantly less training data exhibit comparable correlation levels to English. These insights challenge the prevailing landscape of LLMs suggesting that models centered around languages other than English could provide a more efficient foundation for multilingual applications.
