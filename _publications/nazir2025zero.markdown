---
layout: publication
title: 'Zero-shot Llms In Human-in-the-loop RL: Replacing Human Feedback For Reward Shaping'
authors: Mohammad Saif Nazir, Chayan Banerjee
conference: "Arxiv"
year: 2025
bibkey: nazir2025zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22723"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'RAG', 'Ethics and Bias']
---
Reinforcement learning often faces challenges with reward misalignment, where
agents optimize for given rewards but fail to exhibit the desired behaviors.
This occurs when the reward function incentivizes proxy behaviors that diverge
from the true objective. While human-in-the-loop (HIL) methods can help, they
may exacerbate the problem, as humans are prone to biases that lead to
inconsistent, subjective, or misaligned feedback, complicating the learning
process. To address these issues, we propose two key contributions. First, we
extend the use of zero-shot, off-the-shelf large language models (LLMs) for
reward shaping beyond natural language processing (NLP) to continuous control
tasks. By leveraging LLMs as direct feedback providers, we replace surrogate
models trained on human feedback, which often suffer from the bias inherent in
the feedback data it is trained on. Second, we introduce a hybrid framework
(LLM-HFBF) that enables LLMs to identify and correct biases in human feedback
while incorporating this feedback into the reward shaping process. The LLM-HFBF
framework creates a more balanced and reliable system by addressing both the
limitations of LLMs (e.g., lack of domain-specific knowledge) and human
supervision (e.g., inherent biases). By enabling human feedback bias flagging
and correction, our approach improves reinforcement learning performance and
reduces reliance on potentially biased human guidance. Empirical experiments
show that biased human feedback significantly reduces performance, with average
episodic reward (AER) dropping from 28.472 in (unbiased approaches) to 7.039
(biased with conservative bias). In contrast, LLM-based approaches maintain a
matching AER like unbiased feedback, even in custom edge case scenarios.
