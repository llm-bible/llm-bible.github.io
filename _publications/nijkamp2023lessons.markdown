---
layout: publication
title: 'Codegen2: Lessons For Training Llms On Programming And Natural Languages'
authors: Erik Nijkamp, Hiroaki Hayashi, Caiming Xiong, Silvio Savarese, Yingbo Zhou
conference: Arxiv
year: 2023
citations: 23
bibkey: nijkamp2023lessons
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.02309'}, {name: Code,
    url: 'https://github.com/salesforce/CodeGen'}]
tags: [Scaling Laws, Pre-Training, Efficiency and Optimization, Language Modeling,
  Model Architecture, Training Techniques]
---
Large language models (LLMs) have demonstrated remarkable abilities in
representation learning for program synthesis and understanding tasks. The
quality of the learned representations appears to be dictated by the neural
scaling laws as a function of the number of model parameters and observations,
while imposing upper bounds on the model performance by the amount of available
data and compute, which is costly.
  In this study, we attempt to render the training of LLMs for program
synthesis more efficient by unifying four key components: (1) model
architectures, (2) learning methods, (3) infill sampling, and, (4) data
distributions. Specifically, for the model architecture, we attempt to unify
encoder and decoder-based models into a single prefix-LM. For learning methods,
(i) causal language modeling, (ii) span corruption, (iii) infilling are unified
into a simple learning algorithm. For infill sampling, we explore the claim of
a "free lunch" hypothesis. For data distributions, the effect of a mixture
distribution and multi-epoch training of programming and natural languages on
model performance is explored.
  We conduct a comprehensive series of empirical experiments on 1B LLMs, for
which failures and successes of this exploration are distilled into five
lessons. We will provide a final recipe for training and release CodeGen2
models in size 1B, 3.7B, 7B, and, 16B parameters, along with the training
framework as open-source: https://github.com/salesforce/CodeGen.