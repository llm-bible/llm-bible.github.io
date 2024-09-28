---
layout: publication
title: Decoding by Contrasting Knowledge Enhancing LLMs Confidence on Edited Facts
authors: Bi Baolong, Liu Shenghua, Mei Lingrui, Wang Yiwei, Ji Pengliang, Cheng Xueqi
conference: "Arxiv"
year: 2024
bibkey: bi2024decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11613"}
  - {name: "Code", url: "https://deck-llm.meirtz.com)"}
tags: ['ARXIV', 'Has Code', 'Interpretability And Interpretability', 'LLM', 'Pretraining Methods', 'Training Techniques']
---
The knowledge within large language models (LLMs) may become outdated quickly. While in-context editing (ICE) is currently the most effective method for knowledge editing (KE) it is constrained by the black-box modeling of LLMs and thus lacks interpretability. Our work aims to elucidate the superior performance of ICE on the KE by analyzing the impacts of in-context new knowledge on token-wise distributions. We observe that despite a significant boost in logits of the new knowledge the performance of is still hindered by stubborn knowledge. Stubborn knowledge refers to as facts that have gained excessive confidence during pretraining making it hard to edit effectively. To address this issue and further enhance the performance of ICE we propose a novel approach termed textbfDecoding by textbfContrasting textbfKnowledge (DeCK). DeCK derives the distribution of the next token by contrasting the logits obtained from the newly edited knowledge guided by ICE with those from the unedited parametric knowledge. Our experiments consistently demonstrate that DeCK enhances the confidence of LLMs in edited facts. For instance it improves the performance of LLaMA3-8B-instruct on MQuAKE by up to 219 demonstrating its capability to strengthen ICE in the editing of stubborn knowledge. Our work paves the way to develop the both effective and accountable KE methods for LLMs. (The source code is available at https://deck-llm.meirtz.com)
