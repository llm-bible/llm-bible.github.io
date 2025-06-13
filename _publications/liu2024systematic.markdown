---
layout: publication
title: 'Zhoblimp: A Systematic Assessment Of Language Models With Linguistic Minimal Pairs In Chinese'
authors: Yikang Liu, Yeting Shen, Hongao Zhu, Lilong Xu, Zhiheng Qian, Siyuan Song, Kejia Zhang, Jialong Tang, Pei Zhang, Baosong Yang, Rui Wang, Hai Hu
conference: "Arxiv"
year: 2024
bibkey: liu2024systematic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06096"}
tags: ['RAG']
---
Whether and how language models (LMs) acquire the syntax of natural languages
has been widely evaluated under the minimal pair paradigm. However, a lack of
wide-coverage benchmarks in languages other than English has constrained
systematic investigations into the issue. Addressing it, we first introduce
ZhoBLiMP, the most comprehensive benchmark of linguistic minimal pairs for
Chinese to date, with 118 paradigms, covering 15 linguistic phenomena. We then
train 20 LMs of different sizes (14M to 1.4B) on Chinese corpora of various
volumes (100M to 3B tokens) and evaluate them along with 14 off-the-shelf LLMs
on ZhoBLiMP. The overall results indicate that Chinese grammar can be mostly
learned by models with around 500M parameters, trained on 1B tokens with one
epoch, showing limited benefits for further scaling. Most (N=95) linguistic
paradigms are of easy or medium difficulty for LMs, while there are still 13
paradigms that remain challenging even for models with up to 32B parameters. In
regard to how LMs acquire Chinese grammar, we observe a U-shaped learning
pattern in several phenomena, similar to those observed in child language
acquisition.
