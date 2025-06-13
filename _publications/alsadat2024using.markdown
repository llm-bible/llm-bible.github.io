---
layout: publication
title: 'Using Large Language Models To Automate And Expedite Reinforcement Learning With Reward Machine'
authors: Shayan Meshkat Alsadat, Jean-raphael Gaglione, Daniel Neider, Ufuk Topcu, Zhe Xu
conference: "Arxiv"
year: 2024
bibkey: alsadat2024using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07069"}
tags: ['Few-Shot', 'Agentic', 'Prompting', 'Reinforcement Learning']
---
We present LARL-RM (Large language model-generated Automaton for
Reinforcement Learning with Reward Machine) algorithm in order to encode
high-level knowledge into reinforcement learning using automaton to expedite
the reinforcement learning. Our method uses Large Language Models (LLM) to
obtain high-level domain-specific knowledge using prompt engineering instead of
providing the reinforcement learning algorithm directly with the high-level
knowledge which requires an expert to encode the automaton. We use
chain-of-thought and few-shot methods for prompt engineering and demonstrate
that our method works using these approaches. Additionally, LARL-RM allows for
fully closed-loop reinforcement learning without the need for an expert to
guide and supervise the learning since LARL-RM can use the LLM directly to
generate the required high-level knowledge for the task at hand. We also show
the theoretical guarantee of our algorithm to converge to an optimal policy. We
demonstrate that LARL-RM speeds up the convergence by 30% by implementing our
method in two case studies.
