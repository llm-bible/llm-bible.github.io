---
layout: publication
title: Two Stacks Are Better Than One: A Comparison Of Language Modeling And Translation As Multilingual Pretraining Objectives
authors: Li Zihao, Ji Shaoxiong, Mickus Timothee, Segonne Vincent, Tiedemann Jörg
conference: "Arxiv"
year: 2024
bibkey: li2024two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15489"}
  - {name: "Code", url: "https://github.com/Helsinki-NLP/lm-vs-mt"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Pretrained language models (PLMs) display impressive performances and have captured the attention of the NLP community. Establishing the best practices in pretraining has therefore become a major point of focus for much of NLP research -- especially since the insights developed for monolingual English models need not carry to more complex multilingual. One significant caveat of the current state of the art is that different works are rarely comparable they often discuss different parameter counts training data and evaluation methodology. This paper proposes a comparison of multilingual pretraining objectives in a controlled methodological environment. We ensure that training data and model architectures are comparable and discuss the downstream performances across 6 languages that we observe in probing and fine-tuning scenarios. We make two key observations (1) the architecture dictates which pretraining objective is optimal; (2) multilingual translation is a very effective pre-training objective under the right conditions. We make our code data and model weights available at (texttt)(url)https://github.com/Helsinki-NLP/lm-vs-mt\}\}."
