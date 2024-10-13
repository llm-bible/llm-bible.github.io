---
layout: publication
title: 'On Overcoming Miscalibrated Conversational Priors In Llm-based Chatbots'
authors: Herlihy Christine, Neville Jennifer, Schnabel Tobias, Swaminathan Adith
conference: "Arxiv"
year: 2024
bibkey: herlihy2024overcoming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.01633"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
We explore the use of Large Language Model (LLM-based) chatbots to power
recommender systems. We observe that the chatbots respond poorly when they
encounter under-specified requests (e.g., they make incorrect assumptions,
hedge with a long response, or refuse to answer). We conjecture that such
miscalibrated response tendencies (i.e., conversational priors) can be
attributed to LLM fine-tuning using annotators -- single-turn annotations may
not capture multi-turn conversation utility, and the annotators' preferences
may not even be representative of users interacting with a recommender system.
  We first analyze public LLM chat logs to conclude that query
under-specification is common. Next, we study synthetic recommendation problems
with configurable latent item utilities and frame them as Partially Observed
Decision Processes (PODP). We find that pre-trained LLMs can be sub-optimal for
PODPs and derive better policies that clarify under-specified queries when
appropriate. Then, we re-calibrate LLMs by prompting them with learned control
messages to approximate the improved policy. Finally, we show empirically that
our lightweight learning approach effectively uses logged conversation data to
re-calibrate the response strategies of LLM-based chatbots for recommendation
tasks.
