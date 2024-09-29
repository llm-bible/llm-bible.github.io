---
layout: publication
title: Self45;repetition In Abstractive Neural Summarizers
authors: Salkar Nikita, Trikalinos Thomas, Wallace Byron C., Nenkova Ani
conference: "Arxiv"
year: 2022
bibkey: salkar2022self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.08145"}
tags: ['Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We provide a quantitative and qualitative analysis of self45;repetition in the output of neural summarizers. We measure self45;repetition as the number of n45;grams of length four or longer that appear in multiple outputs of the same system. We analyze the behavior of three popular architectures (BART T5 and Pegasus) fine45;tuned on five datasets. In a regression analysis we find that the three architectures have different propensities for repeating content across output summaries for inputs with BART being particularly prone to self45;repetition. Fine45;tuning on more abstractive data and on data featuring formulaic language is associated with a higher rate of self45;repetition. In qualitative analysis we find systems produce artefacts such as ads and disclaimers unrelated to the content being summarized as well as formulaic phrases common in the fine45;tuning domain. Our approach to corpus45;level analysis of self45;repetition may help practitioners clean up training data for summarizers and ultimately support methods for minimizing the amount of self45;repetition.
