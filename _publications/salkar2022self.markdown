---
layout: publication
title: 'Self-repetition In Abstractive Neural Summarizers'
authors: Nikita Salkar, Thomas Trikalinos, Byron C. Wallace, Ani Nenkova
conference: "Arxiv"
year: 2022
bibkey: salkar2022self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.08145"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
We provide a quantitative and qualitative analysis of self-repetition in the
output of neural summarizers. We measure self-repetition as the number of
n-grams of length four or longer that appear in multiple outputs of the same
system. We analyze the behavior of three popular architectures (BART, T5, and
Pegasus), fine-tuned on five datasets. In a regression analysis, we find that
the three architectures have different propensities for repeating content
across output summaries for inputs, with BART being particularly prone to
self-repetition. Fine-tuning on more abstractive data, and on data featuring
formulaic language, is associated with a higher rate of self-repetition. In
qualitative analysis we find systems produce artefacts such as ads and
disclaimers unrelated to the content being summarized, as well as formulaic
phrases common in the fine-tuning domain. Our approach to corpus-level analysis
of self-repetition may help practitioners clean up training data for
summarizers and ultimately support methods for minimizing the amount of
self-repetition.
