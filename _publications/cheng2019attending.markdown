---
layout: publication
title: Attending To Entities For Better Text Understanding
authors: Cheng Pengxiang, Erk Katrin
conference: "Arxiv"
year: 2019
bibkey: cheng2019attending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1911.04361"}
tags: ['Attention Mechanism', 'BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent progress in NLP witnessed the development of large45;scale pre45;trained language models (GPT BERT XLNet etc.) based on Transformer (Vaswani et al. 2017) and in a range of end tasks such models have achieved state45;of45;the45;art results approaching human performance. This demonstrates the power of the stacked self45;attention architecture when paired with a sufficient number of layers and a large amount of pre45;training data. However on tasks that require complex and long45;distance reasoning where surface45;level cues are not enough there is still a large gap between the pre45;trained models and human performance. Strubell et al. (2018) recently showed that it is possible to inject knowledge of syntactic structure into a model through supervised self45;attention. We conjecture that a similar injection of semantic knowledge in particular coreference information into an existing model would improve performance on such complex problems. On the LAMBADA (Paperno et al. 2016) task we show that a model trained from scratch with coreference as auxiliary supervision for self45;attention outperforms the largest GPT45;2 model setting the new state45;of45;the45;art while only containing a tiny fraction of parameters compared to GPT45;2. We also conduct a thorough analysis of different variants of model architectures and supervision configurations suggesting future directions on applying similar techniques to other problems.
