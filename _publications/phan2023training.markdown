---
layout: publication
title: Training Chain-of-Thought via Latent-Variable Inference
authors: Phan Du, Hoffman Matthew D., Dohan David, Douglas Sholto, Le Tuan Anh, Parisi Aaron, Sountsov Pavel, Sutton Charles, Vikram Sharad, Saurous Rif A.
conference: "Arxiv"
year: 2023
bibkey: phan2023training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02179"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) solve problems more accurately and interpretably when instructed to work out the answer step by step using a chain-of-thought (CoT) prompt. One can also improve LLMs performance on a specific task by supervised fine-tuning i.e. by using gradient ascent on some tunable parameters to maximize the average log-likelihood of correct answers from a labeled training set. Naively combining CoT with supervised tuning requires supervision not just of the correct answers but also of detailed rationales that lead to those answers; these rationales are expensive to produce by hand. Instead we propose a fine-tuning strategy that tries to maximize the emphmarginal log-likelihood of generating a correct answer using CoT prompting approximately averaging over all possible rationales. The core challenge is sampling from the posterior over rationales conditioned on the correct answer; we address it using a simple Markov-chain Monte Carlo (MCMC) expectation-maximization (EM) algorithm inspired by the self-taught reasoner (STaR) memoized wake-sleep Markovian score climbing and persistent contrastive divergence. This algorithm also admits a novel control-variate technique that drives the variance of our gradient estimates to zero as the model improves. Applying our technique to GSM8K and the tasks in BIG-Bench Hard we find that this MCMC-EM fine-tuning technique typically improves the models accuracy on held-out examples more than STaR or prompt-tuning with or without CoT.
