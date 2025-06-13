---
layout: publication
title: 'Increasing The Performance Of Cognitively Inspired Data-efficient Language Models Via Implicit Structure Building'
authors: Omar Momen, David Arps, Laura Kallmeyer
conference: "Arxiv"
year: 2023
bibkey: momen2023increasing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20589"}
tags: ['Transformer', 'Ethics and Bias', 'Model Architecture', 'Masked Language Model', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
In this paper, we describe our submission to the BabyLM Challenge 2023 shared
task on data-efficient language model (LM) pretraining (Warstadt et al., 2023).
We train transformer-based masked language models that incorporate unsupervised
predictions about hierarchical sentence structure into the model architecture.
Concretely, we use the Structformer architecture (Shen et al., 2021) and
variants thereof. StructFormer models have been shown to perform well on
unsupervised syntactic induction based on limited pretraining data, and to
yield performance improvements over a vanilla transformer architecture (Shen et
al., 2021). Evaluation of our models on 39 tasks provided by the BabyLM
challenge shows promising improvements of models that integrate a hierarchical
bias into the architecture at some particular tasks, even though they fail to
consistently outperform the RoBERTa baseline model provided by the shared task
organizers on all tasks.
