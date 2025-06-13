---
layout: publication
title: 'Adversarial Tokenization'
authors: Renato Lui Geh, Zilei Shao, Guy Van Den Broeck
conference: "Arxiv"
year: 2025
bibkey: geh2025adversarial
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.02174'}
tags: ['Responsible AI', 'Security', 'Tokenization', 'Training Techniques']
---
Current LLM pipelines account for only one possible tokenization for a given
string, ignoring exponentially many alternative tokenizations during training
and inference. For example, the standard Llama3 tokenization of penguin is
[p,enguin], yet [peng,uin] is another perfectly valid alternative. In this
paper, we show that despite LLMs being trained solely on one tokenization, they
still retain semantic understanding of other tokenizations, raising questions
about their implications in LLM safety. Put succinctly, we answer the following
question: can we adversarially tokenize an obviously malicious string to evade
safety and alignment restrictions? We show that not only is adversarial
tokenization an effective yet previously neglected axis of attack, but it is
also competitive against existing state-of-the-art adversarial approaches
without changing the text of the harmful request. We empirically validate this
exploit across three state-of-the-art LLMs and adversarial datasets, revealing
a previously unknown vulnerability in subword models.
