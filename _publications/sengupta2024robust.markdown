---
layout: publication
title: 'Robust And Efficient Fine-tuning Of Llms With Bayesian Reparameterization Of Low-rank Adaptation'
authors: Ayan Sengupta, Vaibhav Seth, Arinjay Pathak, Natraj Raman, Sriram Gopalakrishnan, Tanmoy Chakraborty
conference: "Arxiv"
year: 2024
bibkey: sengupta2024robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.04358"}
tags: ['Fine-Tuning', 'Ethics and Bias', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
Large Language Models (LLMs) are highly resource-intensive to fine-tune due
to their enormous size. While low-rank adaptation is a prominent
parameter-efficient fine-tuning approach, it suffers from sensitivity to
hyperparameter choices, leading to instability in model performance on
fine-tuning downstream tasks. This paper highlights the importance of effective
parameterization in low-rank fine-tuning to reduce estimator variance and
enhance the stability of final model outputs. We propose MonteCLoRA, an
efficient fine-tuning technique, employing Monte Carlo estimation to learn an
unbiased posterior estimation of low-rank parameters with low expected
variance, which stabilizes fine-tuned LLMs with only O(1) additional
parameters. MonteCLoRA shows significant improvements in accuracy and
robustness, achieving up to 3.8% higher accuracy and 8.6% greater robustness
than existing efficient fine-tuning methods on natural language understanding
tasks with pre-trained RoBERTa-base. Furthermore, in generative tasks with
pre-trained LLaMA-1-7B, MonteCLoRA demonstrates robust zero-shot performance
with 50% lower variance than the contemporary efficient fine-tuning methods.
The theoretical and empirical results presented in the paper underscore how
parameterization and hyperpriors balance exploration-exploitation in the
low-rank parametric space, therefore leading to more optimal and robust
parameter estimation during efficient fine-tuning.
