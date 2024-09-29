---
layout: publication
title: Same Pre45;training Loss Better Downstream Implicit Bias Matters For Language Models
authors: Liu Hong, Xie Sang Michael, Li Zhiyuan, Ma Tengyu
conference: "Arxiv"
year: 2022
bibkey: liu2022same
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.14199"}
tags: ['Ethics And Bias', 'GPT', 'Language Modeling', 'Pretraining Methods', 'Training Techniques']
---
Language modeling on large45;scale datasets leads to impressive performance gains on various downstream language tasks. The validation pre45;training loss (or perplexity in autoregressive language modeling) is often used as the evaluation metric when developing language models since the pre45;training loss tends to be well45;correlated with downstream performance (which is itself difficult to evaluate comprehensively). Contrary to this conventional wisdom this paper shows that 1) pre45;training loss cannot fully explain downstream performance and 2) flatness of the model is well45;correlated with downstream performance where pre45;training loss is not. On simplified datasets we identify three ways to produce models with the same (statistically optimal) pre45;training loss but different downstream performance continue pre45;training after convergence increasing the model size and changing the training algorithm. These experiments demonstrate the existence of implicit bias of pre45;training algorithms/optimizers 45;45; among models with the same minimal pre45;training loss they implicitly prefer more transferable ones. Toward understanding this implicit bias we prove that SGD with standard mini45;batch noise implicitly prefers flatter minima in language models and empirically observe a strong correlation between flatness and downstream performance among models with the same minimal pre45;training loss. We also prove in a synthetic language setting that among the models with the minimal pre45;training loss the flattest model transfers to downstream tasks.
