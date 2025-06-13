---
layout: publication
title: 'Large Language Models Are Biased Reinforcement Learners'
authors: William M. Hayes, Nicolas Yax, Stefano Palminteri
conference: "Arxiv"
year: 2024
bibkey: hayes2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.11422"}
tags: ['Agentic', 'Reinforcement Learning', 'Ethics and Bias', 'Prompting', 'Applications', 'In-Context Learning']
---
In-context learning enables large language models (LLMs) to perform a variety
of tasks, including learning to make reward-maximizing choices in simple bandit
tasks. Given their potential use as (autonomous) decision-making agents, it is
important to understand how these models perform such reinforcement learning
(RL) tasks and the extent to which they are susceptible to biases. Motivated by
the fact that, in humans, it has been widely documented that the value of an
outcome depends on how it compares to other local outcomes, the present study
focuses on whether similar value encoding biases apply to how LLMs encode
rewarding outcomes. Results from experiments with multiple bandit tasks and
models show that LLMs exhibit behavioral signatures of a relative value bias.
Adding explicit outcome comparisons to the prompt produces opposing effects on
performance, enhancing maximization in trained choice sets but impairing
generalization to new choice sets. Computational cognitive modeling reveals
that LLM behavior is well-described by a simple RL algorithm that incorporates
relative values at the outcome encoding stage. Lastly, we present preliminary
evidence that the observed biases are not limited to fine-tuned LLMs, and that
relative value processing is detectable in the final hidden layer activations
of a raw, pretrained model. These findings have important implications for the
use of LLMs in decision-making applications.
