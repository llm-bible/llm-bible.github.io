---
layout: publication
title: 'Ernie-code: Beyond English-centric Cross-lingual Pretraining For Programming Languages'
authors: Chai Yekun, Wang Shuohuan, Pang Chao, Sun Yu, Tian Hao, Wu Hua
conference: "Arxiv"
year: 2022
bibkey: chai2022ernie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.06742"}
tags: ['Applications', 'Efficiency And Optimization', 'Language Modeling', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Software engineers working with the same programming language (PL) may speak
different natural languages (NLs) and vice versa, erecting huge barriers to
communication and working efficiency. Recent studies have demonstrated the
effectiveness of generative pre-training in computer programs, yet they are
always English-centric. In this work, we step towards bridging the gap between
multilingual NLs and multilingual PLs for large language models (LLMs). We
release ERNIE-Code, a unified pre-trained language model for 116 NLs and 6 PLs.
We employ two methods for universal cross-lingual pre-training: span-corruption
language modeling that learns patterns from monolingual NL or PL; and
pivot-based translation language modeling that relies on parallel data of many
NLs and PLs. Extensive results show that ERNIE-Code outperforms previous
multilingual LLMs for PL or NL across a wide range of end tasks of code
intelligence, including multilingual code-to-text, text-to-code, code-to-code,
and text-to-text generation. We further show its advantage of zero-shot
prompting on multilingual code summarization and text-to-text translation. We
release our code and pre-trained checkpoints.
