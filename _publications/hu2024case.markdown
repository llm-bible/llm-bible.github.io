---
layout: publication
title: Case45;based Or Rule45;based How Do Transformers Do The Math
authors: Hu Yi, Tang Xiaojuan, Yang Haotong, Zhang Muhan
conference: "Arxiv"
year: 2024
bibkey: hu2024case
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17709"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Despite the impressive performance in a variety of complex tasks modern large language models (LLMs) still have trouble dealing with some math problems that are simple and intuitive for humans such as addition. While we can easily learn basic rules of addition and apply them to new problems of any length LLMs struggle to do the same. Instead they may rely on similar cases seen in the training corpus for help. We define these two different reasoning mechanisms as rule45;based reasoning and case45;based reasoning. Since rule45;based reasoning is essential for acquiring systematic generalization ability we aim to explore exactly whether transformers use rule45;based or case45;based reasoning for math problems. Through carefully designed intervention experiments on five math tasks we confirm that transformers are performing case45;based reasoning no matter whether scratchpad is used which aligns with the previous observations that transformers use subgraph matching/shortcut learning to reason. To mitigate such problems we propose a Rule45;Following Fine45;Tuning (RFFT) technique to teach transformers to perform rule45;based reasoning. Specifically we provide explicit rules in the input and then instruct transformers to recite and follow the rules step by step. Through RFFT we successfully enable LLMs fine45;tuned on 145;5 digit addition to generalize to up to 1245;digit addition with over 9537; accuracy which is over 4037; higher than scratchpad. The significant improvement demonstrates that teaching LLMs to use rules explicitly helps them learn rule45;based reasoning and generalize better in length.
