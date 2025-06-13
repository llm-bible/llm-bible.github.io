---
layout: publication
title: 'Anticipating Future With Large Language Model For Simultaneous Machine Translation'
authors: Siqi Ouyang, Oleksii Hrinchuk, Zhehuai Chen, Vitaly Lavrukhin, Jagadeesh Balam, Lei Li, Boris Ginsburg
conference: "Arxiv"
year: 2024
bibkey: ouyang2024anticipating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.22499"}
  - {name: "Code", url: "https://github.com/owaski/TAF"}
tags: ['Training Techniques', 'Has Code', 'Applications', 'Reinforcement Learning']
---
Simultaneous machine translation (SMT) takes streaming input utterances and incrementally produces target text. Existing SMT methods mainly use the partial utterance that has already arrived at the input and the generated hypothesis. Motivated by human interpreters' technique to forecast future words before hearing them, we propose \\(\textbf\{T\}\\)ranslation by \\(\textbf\{A\}\\)nticipating \\(\textbf\{F\}\\)uture (TAF), a method to improve translation quality while retraining low latency. Its core idea is to use a large language model (LLM) to predict future source words and opportunistically translate without introducing too much risk. We evaluate our TAF and multiple baselines of SMT on four language directions. Experiments show that TAF achieves the best translation quality-latency trade-off and outperforms the baselines by up to 5 BLEU points at the same latency (three words). Code is released at https://github.com/owaski/TAF
