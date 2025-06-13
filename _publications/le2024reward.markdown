---
layout: publication
title: '\(i\)repo: \(i\)mplicit Reward Pairwise Difference Based Empirical Preference Optimization'
authors: Long Tan Le, Han Shu, Tung-anh Nguyen, Choong Seon Hong, Nguyen H. Tran
conference: "Arxiv"
year: 2024
bibkey: le2024reward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15230"}
tags: ['Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'Reinforcement Learning']
---
While astonishingly capable, large Language Models (LLM) can sometimes
produce outputs that deviate from human expectations. Such deviations
necessitate an alignment phase to prevent disseminating untruthful, toxic, or
biased information. Traditional alignment methods based on reinforcement
learning often struggle with the identified instability, whereas preference
optimization methods are limited by their overfitting to pre-collected
hard-label datasets. In this paper, we propose a novel LLM alignment framework
named \\(i\\)REPO, which utilizes implicit Reward pairwise difference regression
for Empirical Preference Optimization. Particularly, \\(i\\)REPO employs
self-generated datasets labeled by empirical human (or AI annotator) preference
to iteratively refine the aligned policy through a novel regression-based loss
function. Furthermore, we introduce an innovative algorithm backed by
theoretical guarantees for achieving optimal results under ideal assumptions
and providing a practical performance-gap result without such assumptions.
Experimental results with Phi-2 and Mistral-7B demonstrate that \\(i\\)REPO
effectively achieves self-alignment using soft-label, self-generated responses
and the logit of empirical AI annotators. Furthermore, our approach surpasses
preference optimization baselines in evaluations using the Language Model
Evaluation Harness and Multi-turn benchmarks.
