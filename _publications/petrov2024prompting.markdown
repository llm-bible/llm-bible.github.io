---
layout: publication
title: Prompting A Pretrained Transformer Can Be A Universal Approximator
authors: Petrov Aleksandar, Torr Philip H. S., Bibi Adel
conference: "Arxiv"
year: 2024
bibkey: petrov2024prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14753"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
Despite the widespread adoption of prompting prompt tuning and prefix45;tuning of transformer models our theoretical understanding of these fine45;tuning methods remains limited. A key question is whether one can arbitrarily modify the behavior of pretrained model by prompting or prefix45;tuning it. Formally whether prompting and prefix45;tuning a pretrained model can universally approximate sequence45;to45;sequence functions. This paper answers in the affirmative and demonstrates that much smaller pretrained models than previously thought can be universal approximators when prefixed. In fact the attention mechanism is uniquely suited for universal approximation with prefix45;tuning a single attention head being sufficient to approximate any continuous function. Moreover any sequence45;to45;sequence function can be approximated by prefixing a transformer with depth linear in the sequence length. Beyond these density45;type results we also offer Jackson45;type bounds on the length of the prefix needed to approximate a function to a desired precision.
