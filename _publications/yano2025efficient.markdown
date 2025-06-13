---
layout: publication
title: 'Efficient Construction Of Model Family Through Progressive Training Using Model Expansion'
authors: Kazuki Yano, Sho Takase, Sosuke Kobayashi, Shun Kiyono, Jun Suzuki
conference: "Arxiv"
year: 2025
bibkey: yano2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.00623'}
tags: ['Training Techniques']
---
As Large Language Models (LLMs) gain widespread practical application,
providing the model family of different parameter sizes has become standard
practice to address diverse computational requirements. Conventionally, each
model in a family is trained independently, resulting in computational costs
that scale additively with the number of models. We propose an efficient method
for constructing the model family through progressive training, where smaller
models are incrementally expanded to larger sizes to create a complete model
family. Through extensive experiments with a model family ranging from 1B to 8B
parameters, we demonstrate that our method reduces computational costs by
approximately 25% while maintaining comparable performance to independently
trained models. Furthermore, by strategically adjusting maximum learning rates
based on model size, our method outperforms the independent training across
various metrics. Beyond performance gains, our approach offers an additional
advantage: models in our family tend to yield more consistent behavior across
different model sizes.
