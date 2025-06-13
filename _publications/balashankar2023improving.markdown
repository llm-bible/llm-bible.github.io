---
layout: publication
title: 'Improving Few-shot Generalization Of Safety Classifiers Via Data Augmented Parameter-efficient Fine-tuning'
authors: Ananth Balashankar, Xiao Ma, Aradhana Sinha, Ahmad Beirami, Yao Qin, Jilin Chen, Alex Beutel
conference: "Arxiv"
year: 2023
bibkey: balashankar2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16959"}
tags: ['Fine-Tuning', 'Responsible AI', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting']
---
As large language models (LLMs) are widely adopted, new safety issues and
policies emerge, to which existing safety classifiers do not generalize well.
If we have only observed a few examples of violations of a new safety rule, how
can we build a classifier to detect violations? In this paper, we study the
novel setting of domain-generalized few-shot learning for LLM-based text safety
classifiers. Unlike prior few-shot work, these new safety issues can be hard to
uncover and we do not get to choose the few examples. We demonstrate that
existing few-shot techniques do not perform well in this setting, and rather we
propose to do parameter-efficient fine-tuning (PEFT) combined with augmenting
training data based on similar examples in prior existing rules. We empirically
show that our approach of similarity-based data-augmentation + prompt-tuning
(DAPT) consistently outperforms baselines that either do not rely on data
augmentation or on PEFT by 7-17% F1 score in the Social Chemistry moral
judgement and 9-13% AUC in the Toxicity detection tasks, even when the new rule
is loosely correlated with existing ones.
