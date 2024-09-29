---
layout: publication
title: Tokenization Falling Short\: The Curse Of Tokenization
authors: Chai Yekun, Fang Yewei, Peng Qiwei, Li Xuhong
conference: "Arxiv"
year: 2024
bibkey: chai2024tokenization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11687"}
tags: ['Ethics And Bias', 'Tokenization']
---
Language models typically tokenize raw text into sequences of subword identifiers from a predefined vocabulary a process inherently sensitive to typographical errors length variations and largely oblivious to the internal structure of tokens-issues we term the curse of tokenization. In this study we delve into these drawbacks and demonstrate that large language models (LLMs) remain susceptible to these problems. This study systematically investigates these challenges and their impact on LLMs through three critical research questions (1) complex problem solving (2) token structure probing and (3) resilience to typographical variation. Our findings reveal that scaling model parameters can mitigate the issue of tokenization; however LLMs still suffer from biases induced by typos and other text format variations. Our experiments show that subword regularization such as BPE-dropout can mitigate this issue. We will release our code and data to facilitate further research.
