---
layout: publication
title: 'An In-depth Investigation Of User Response Simulation For Conversational Search'
authors: Zhenduo Wang, Zhichao Xu, Qingyao Ai, Vivek Srikumar
conference: "Arxiv"
year: 2023
bibkey: wang2023investigation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.07944"}
tags: ['Training Techniques', 'GPT', 'Attention Mechanism', 'Model Architecture']
---
Conversational search has seen increased recent attention in both the IR and
NLP communities. It seeks to clarify and solve users' search needs through
multi-turn natural language interactions. However, most existing systems are
trained and demonstrated with recorded or artificial conversation logs.
Eventually, conversational search systems should be trained, evaluated, and
deployed in an open-ended setting with unseen conversation trajectories. A key
challenge is that training and evaluating such systems both require a
human-in-the-loop, which is expensive and does not scale. One strategy is to
simulate users, thereby reducing the scaling costs. However, current user
simulators are either limited to only responding to yes-no questions from the
conversational search system or unable to produce high-quality responses in
general.
  In this paper, we show that existing user simulation systems could be
significantly improved by a smaller finetuned natural language generation
model. However, rather than merely reporting it as the new state-of-the-art, we
consider it a strong baseline and present an in-depth investigation of
simulating user response for conversational search. Our goal is to supplement
existing work with an insightful hand-analysis of unsolved challenges by the
baseline and propose our solutions. The challenges we identified include (1) a
blind spot that is difficult to learn, and (2) a specific type of misevaluation
in the standard setup. We propose a new generation system to effectively cover
the training blind spot and suggest a new evaluation setup to avoid
misevaluation. Our proposed system leads to significant improvements over
existing systems and large language models such as GPT-4. Additionally, our
analysis provides insights into the nature of user simulation to facilitate
future work.
