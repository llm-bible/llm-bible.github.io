---
layout: publication
title: 'Unpaired Cross-lingual Image Caption Generation With Self-supervised Rewards'
authors: Song Yuqing, Chen Shizhe, Zhao Yida, Jin Qin
conference: "Arxiv"
year: 2019
bibkey: song2019unpaired
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1908.05407"}
tags: ['Applications', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Generating image descriptions in different languages is essential to satisfy
users worldwide. However, it is prohibitively expensive to collect large-scale
paired image-caption dataset for every target language which is critical for
training descent image captioning models. Previous works tackle the unpaired
cross-lingual image captioning problem through a pivot language, which is with
the help of paired image-caption data in the pivot language and pivot-to-target
machine translation models. However, such language-pivoted approach suffers
from inaccuracy brought by the pivot-to-target translation, including
disfluency and visual irrelevancy errors. In this paper, we propose to generate
cross-lingual image captions with self-supervised rewards in the reinforcement
learning framework to alleviate these two types of errors. We employ
self-supervision from mono-lingual corpus in the target language to provide
fluency reward, and propose a multi-level visual semantic matching model to
provide both sentence-level and concept-level visual relevancy rewards. We
conduct extensive experiments for unpaired cross-lingual image captioning in
both English and Chinese respectively on two widely used image caption corpora.
The proposed approach achieves significant performance improvement over
state-of-the-art methods.
