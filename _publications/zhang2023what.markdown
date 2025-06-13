---
layout: publication
title: 'What And How Does In-context Learning Learn? Bayesian Model Averaging, Parameterization, And Generalization'
authors: Yufeng Zhang, Fengzhuo Zhang, Zhuoran Yang, Zhaoran Wang
conference: "Arxiv"
year: 2023
bibkey: zhang2023what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.19420"}
tags: ['Transformer', 'Survey Paper', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
In this paper, we conduct a comprehensive study of In-Context Learning (ICL)
by addressing several open questions: (a) What type of ICL estimator is learned
by large language models? (b) What is a proper performance metric for ICL and
what is the error rate? (c) How does the transformer architecture enable ICL?
To answer these questions, we adopt a Bayesian view and formulate ICL as a
problem of predicting the response corresponding to the current covariate,
given a number of examples drawn from a latent variable model. To answer (a),
we show that, without updating the neural network parameters, ICL implicitly
implements the Bayesian model averaging algorithm, which is proven to be
approximately parameterized by the attention mechanism. For (b), we analyze the
ICL performance from an online learning perspective and establish a
\\(\mathcal\{O\}(1/T)\\) regret bound for perfectly pretrained ICL, where \\(T\\) is the
number of examples in the prompt. To answer (c), we show that, in addition to
encoding Bayesian model averaging via attention, the transformer architecture
also enables a fine-grained statistical analysis of pretraining under realistic
assumptions. In particular, we prove that the error of pretrained model is
bounded by a sum of an approximation error and a generalization error, where
the former decays to zero exponentially as the depth grows, and the latter
decays to zero sublinearly with the number of tokens in the pretraining
dataset. Our results provide a unified understanding of the transformer and its
ICL ability with bounds on ICL regret, approximation, and generalization, which
deepens our knowledge of these essential aspects of modern language models.
