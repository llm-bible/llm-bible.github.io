---
layout: publication
title: 'Massively Multilingual Shallow Fusion With Large Language Models'
authors: Ke Hu, Tara N. Sainath, Bo Li, Nan Du, Yanping Huang, Andrew M. Dai, Yu Zhang, Rodrigo Cabrera, Zhifeng Chen, Trevor Strohman
conference: "Arxiv"
year: 2023
bibkey: hu2023massively
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2302.08917'}
tags: ['RAG', 'INTERSPEECH', 'Merging']
---
While large language models (LLM) have made impressive progress in natural
language processing, it remains unclear how to utilize them in improving
automatic speech recognition (ASR). In this work, we propose to train a single
multilingual language model (LM) for shallow fusion in multiple languages. We
push the limits of the multilingual LM to cover up to 84 languages by scaling
up using a mixture-of-experts LLM, i.e., generalist language model (GLaM). When
the number of experts increases, GLaM dynamically selects only two at each
decoding step to keep the inference computation roughly constant. We then apply
GLaM to a multilingual shallow fusion task based on a state-of-the-art
end-to-end model. Compared to a dense LM of similar computation during
inference, GLaM reduces the WER of an English long-tail test set by 4.4%
relative. In a multilingual shallow fusion task, GLaM improves 41 out of 50
languages with an average relative WER reduction of 3.85%, and a maximum
reduction of 10%. Compared to the baseline model, GLaM achieves an average WER
reduction of 5.53% over 43 languages.
