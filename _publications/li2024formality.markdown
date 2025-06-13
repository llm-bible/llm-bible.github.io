---
layout: publication
title: 'Formality Is Favored: Unraveling The Learning Preferences Of Large Language Models On Data With Conflicting Knowledge'
authors: Jiahuan Li, Yiqing Cao, Shujian Huang, Jiajun Chen
conference: "Arxiv"
year: 2024
bibkey: li2024formality
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04784"}
tags: ['Pretraining Methods', 'Training Techniques']
---
Having been trained on massive pretraining data, large language models have
shown excellent performance on many knowledge-intensive tasks. However,
pretraining data tends to contain misleading and even conflicting information,
and it is intriguing to understand how LLMs handle these noisy data during
training. In this study, we systematically analyze LLMs' learning preferences
for data with conflicting knowledge. We find that pretrained LLMs establish
learning preferences similar to humans, i.e., preferences towards formal texts
and texts with fewer spelling errors, resulting in faster learning and more
favorable treatment of knowledge in data with such features when facing
conflicts. This finding is generalizable across models and languages and is
more evident in larger models. An in-depth analysis reveals that LLMs tend to
trust data with features that signify consistency with the majority of data,
and it is possible to instill new preferences and erase old ones by
manipulating the degree of consistency with the majority data.
