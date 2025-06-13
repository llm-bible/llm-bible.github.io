---
layout: publication
title: 'Beyond The Binary: Capturing Diverse Preferences With Reward Regularization'
authors: Vishakh Padmakumar, Chuanyang Jin, Hannah Rose Kirk, He He
conference: "Arxiv"
year: 2024
bibkey: padmakumar2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.03822"}
tags: ['Prompting', 'Training Techniques', 'Reinforcement Learning']
---
Large language models (LLMs) are increasingly deployed via public-facing
interfaces to interact with millions of users, each with diverse preferences.
Despite this, preference tuning of LLMs predominantly relies on reward models
trained using binary judgments where annotators select the preferred choice out
of pairs of model outputs. In this work, we argue that this reliance on binary
choices does not capture the broader, aggregate preferences of the target user
in real-world tasks. We propose a taxonomy that identifies two dimensions of
subjectivity where different users disagree on the preferred output-namely, the
Plurality of Responses to Prompts, where prompts allow for multiple correct
answers, and the Indistinguishability of Responses, where candidate outputs are
paraphrases of each other. We show that reward models correlate weakly with
user preferences in these cases. As a first step to address this issue, we
introduce a simple yet effective method that augments existing binary
preference datasets with synthetic preference judgments to estimate potential
user disagreement. Incorporating these via a margin term as a form of
regularization during model training yields predictions that better align with
the aggregate user preferences.
