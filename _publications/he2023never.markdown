---
layout: publication
title: 'Never Lost In The Middle: Mastering Long-context Question Answering With Position-agnostic Decompositional Training'
authors: Junqing He, Kunhao Pan, Xiaoqun Dong, Zhuoyang Song, Yibo Liu, Qianguo Sun, Yuxin Liang, Hao Wang, Enming Zhang, Jiaxing Zhang
conference: "Arxiv"
year: 2023
bibkey: he2023never
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09198"}
tags: ['Training Techniques', 'Attention Mechanism', 'Applications', 'Model Architecture']
---
While large language models (LLMs) are equipped with longer text input
capabilities than before, they are struggling to seek correct information in
long contexts. The "lost in the middle" problem challenges most LLMs, referring
to the dramatic decline in accuracy when correct information is located in the
middle. To overcome this crucial issue, this paper proposes to enhance the
information searching and reflection ability of LLMs in long contexts via
specially designed tasks called Attention Strengthening Multi-doc QA (ASM QA).
Following these tasks, our model excels in focusing more precisely on the
desired information. Experimental results show substantial improvement in
Multi-doc QA and other benchmarks, superior to state-of-the-art models by 13.7%
absolute gain in shuffled settings, by 21.5% in passage retrieval task. We
release our model, Ziya-Reader to promote related research in the community.
