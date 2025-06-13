---
layout: publication
title: 'Evade The Trap Of Mediocrity: Promoting Diversity And Novelty In Text Generation Via Concentrating Attention'
authors: Wenhao Li, Xiaoyuan Yi, Jinyi Hu, Maosong Sun, Xing Xie
conference: "Arxiv"
year: 2022
bibkey: li2022evade
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.07164"}
tags: ['Transformer', 'Applications', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Recently, powerful Transformer architectures have proven superior in
generating high-quality sentences. Nevertheless, these models tend to produce
dull high-frequency phrases, severely hurting the diversity and novelty of
generated text. In this work, we dig into the intrinsic mechanism of this
problem and found that sparser attention values in Transformer could improve
diversity. To understand such a phenomenon, we first conduct both empirical and
theoretical analysis and then attribute it to representation degeneration
caused by the attentive mixture of the hidden states during training. We term
this process the Trap of Mediocrity. To escape from such a trap, we introduce a
novel attention regularization loss to control the sharpness of the attention
distribution, which is transparent to model structures and can be easily
implemented within 20 lines of python code. We prove that this method could be
mathematically regarded as learning a Bayesian approximation of posterior
attention. Experiments show that our method improved the diversity and novelty
of the generated text while maintaining comparable quality on a variety of
conditional and unconditional generation tasks.
