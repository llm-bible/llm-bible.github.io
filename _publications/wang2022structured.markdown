---
layout: publication
title: 'STRUDEL: Structured Dialogue Summarization For Dialogue Comprehension'
authors: Borui Wang, Chengcheng Feng, Arjun Nair, Madelyn Mao, Jai Desai, Asli Celikyilmaz, Haoran Li, Yashar Mehdad, Dragomir Radev
conference: "Arxiv"
year: 2022
bibkey: wang2022structured
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2212.12652'}
tags: ['Transformer', 'Model Architecture', 'Applications', 'Tools', 'Pretraining Methods']
---
Abstractive dialogue summarization has long been viewed as an important
standalone task in natural language processing, but no previous work has
explored the possibility of whether abstractive dialogue summarization can also
be used as a means to boost an NLP system's performance on other important
dialogue comprehension tasks. In this paper, we propose a novel type of
dialogue summarization task - STRUctured DiaLoguE Summarization - that can help
pre-trained language models to better understand dialogues and improve their
performance on important dialogue comprehension tasks. We further collect human
annotations of STRUDEL summaries over 400 dialogues and introduce a new STRUDEL
dialogue comprehension modeling framework that integrates STRUDEL into a
graph-neural-network-based dialogue reasoning module over transformer encoder
language models to improve their dialogue comprehension abilities. In our
empirical experiments on two important downstream dialogue comprehension tasks
- dialogue question answering and dialogue response prediction - we show that
our STRUDEL dialogue comprehension model can significantly improve the dialogue
comprehension performance of transformer encoder language models.
