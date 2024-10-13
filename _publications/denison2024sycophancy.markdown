---
layout: publication
title: 'Sycophancy To Subterfuge: Investigating Reward-tampering In Large Language Models'
authors: Denison Carson, Macdiarmid Monte, Barez Fazl, Duvenaud David, Kravec Shauna, Marks Samuel, Schiefer Nicholas, Soklaski Ryan, Tamkin Alex, Kaplan Jared, Shlegeris Buck, Bowman Samuel R., Perez Ethan, Hubinger Evan
conference: "Arxiv"
year: 2024
bibkey: denison2024sycophancy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10162"}
tags: ['Agentic', 'Fine Tuning', 'Reinforcement Learning', 'Training Techniques']
---
In reinforcement learning, specification gaming occurs when AI systems learn
undesired behaviors that are highly rewarded due to misspecified training
goals. Specification gaming can range from simple behaviors like sycophancy to
sophisticated and pernicious behaviors like reward-tampering, where a model
directly modifies its own reward mechanism. However, these more pernicious
behaviors may be too complex to be discovered via exploration. In this paper,
we study whether Large Language Model (LLM) assistants which find easily
discovered forms of specification gaming will generalize to perform rarer and
more blatant forms, up to and including reward-tampering. We construct a
curriculum of increasingly sophisticated gameable environments and find that
training on early-curriculum environments leads to more specification gaming on
remaining environments. Strikingly, a small but non-negligible proportion of
the time, LLM assistants trained on the full curriculum generalize zero-shot to
directly rewriting their own reward function. Retraining an LLM not to game
early-curriculum environments mitigates, but does not eliminate,
reward-tampering in later environments. Moreover, adding harmlessness training
to our gameable environments does not prevent reward-tampering. These results
demonstrate that LLMs can generalize from common forms of specification gaming
to more pernicious reward tampering and that such behavior may be nontrivial to
remove.
