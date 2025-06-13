---
layout: publication
title: 'A Comparison Of Language Modeling And Translation As Multilingual Pretraining Objectives'
authors: Zihao Li, Shaoxiong Ji, Timothee Mickus, Vincent Segonne, Jörg Tiedemann
conference: "Arxiv"
year: 2024
bibkey: li2024comparison
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15489"}
  - {name: "Code", url: "https://github.com/Helsinki-NLP/lm-vs-mt"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Attention Mechanism']
---
Pretrained language models (PLMs) display impressive performances and have
captured the attention of the NLP community. Establishing best practices in
pretraining has, therefore, become a major focus of NLP research, especially
since insights gained from monolingual English models may not necessarily apply
to more complex multilingual models. One significant caveat of the current
state of the art is that different works are rarely comparable: they often
discuss different parameter counts, training data, and evaluation methodology.
  This paper proposes a comparison of multilingual pretraining objectives in a
controlled methodological environment. We ensure that training data and model
architectures are comparable, and discuss the downstream performances across 6
languages that we observe in probing and fine-tuning scenarios. We make two key
observations: (1) the architecture dictates which pretraining objective is
optimal; (2) multilingual translation is a very effective pretraining objective
under the right conditions. We make our code, data, and model weights available
at \texttt\{\url\{https://github.com/Helsinki-NLP/lm-vs-mt\}\}.
