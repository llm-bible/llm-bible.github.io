---
layout: publication
title: 'Is In-context Learning Sufficient For Instruction Following In Llms?'
authors: Hao Zhao, Maksym Andriushchenko, Francesco Croce, Nicolas Flammarion
conference: "Arxiv"
year: 2024
bibkey: zhao2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19874"}
  - {name: "Code", url: "https://github.com/tml-epfl/icl-alignment"}
tags: ['Fine-Tuning', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
In-context learning (ICL) allows LLMs to learn from examples without changing
their weights: this is a particularly promising capability for long-context
LLMs that can potentially learn from many examples. Recently, Lin et al. (2024)
proposed URIAL, a method using only three in-context examples to align base
LLMs, achieving non-trivial instruction following performance. In this work, we
show that, while effective, ICL alignment with URIAL still underperforms
compared to instruction fine-tuning on the established benchmark MT-Bench,
especially with more capable base LLMs. We then uncover the most relevant
elements for successful in-context alignment, finding the crucial role of the
decoding parameters. Based on these insights, we show that the approach of
URIAL can indeed be improved by adding high-quality, potentially carefully
selected via greedy search, demonstrations in context, getting closer to the
performance of instruct models. Finally, we provide the first, to our
knowledge, systematic comparison of ICL and instruction fine-tuning (IFT) for
instruction following in the low data regime, where ICL can be a viable
alternative to IFT. Overall, our work advances the understanding of ICL as an
alignment technique and its relationship to IFT. We provide our code at
https://github.com/tml-epfl/icl-alignment.
